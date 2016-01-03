---
layout: post
title:  "Welcome to Boust Bioinformatics!"
date:   2016-01-03 15:02:43
categories: jekyll update
---

Bet I never keep this up-to-date!

Starting a site to keep track of bioinformatics things I'm working on or interested in.

Pretty easy to make fancy highlighted code too, e.g.:

{% highlight python %}

def silly_reverse_complement(dna_string):
  
  """ Always better to use biopython for this! """
  
  complement_dict = { 'A' : 'T', 
                      'C' : 'G', 
                      'G' : 'C', 
                      'T' : 'A' }
  bases = list(dna_string)

  output = ''.join([complement_dict[base] for base in bases][::-1])

  return output

print silly_reverse_complement('TTTAAACCGG')

#=> prints reverse complement of 'TTTAAACCGG' i.e. CCGGTTTAAA .
{% endhighlight %}

Check out the [Jekyll docs][jekyll] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll’s dedicated Help repository][jekyll-help].

[jekyll]:      http://jekyllrb.com
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-help]: https://github.com/jekyll/jekyll-help
