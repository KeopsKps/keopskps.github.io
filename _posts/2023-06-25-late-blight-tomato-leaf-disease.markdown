---
layout: post
title:  "Late Blight Tomato Leaf Disease Classification using FastAI"
date:   2023-06-25 20:30:32 -0600
categories: jekyll update
---

# Introduction

I recently started taking the Practical Deep Learning for Coders course from FastAI. In lesson 0 of this course, Jeremy explains the importance of taking a practical approach of this course, instead of only watching lectures it's important that you start building something from what you learned from very first lecture. So, based on that recommendation, on the first lecture we take a look to some `learners` availables in the FastAI library. These learners are based on common tasks in deep learning like image classification, image segmentation and text classification. 

In this post I will be working on reproducing the vision learner developed in the lecture to classify cats vs no cats in an image, but for a different dataset. This can be easily done in Kaggle by looking in the dataset section, then you will find filters of common types of dataset, in this case, I'm looking for classification datasets:

[Kaggle Classification datasets](../_site/assets/kaggle_datasets_classification.png)

You’ll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. You can rebuild the site in many different ways, but the most common way is to run `jekyll serve`, which launches a web server and auto-regenerates your site when a file is updated.

Jekyll requires blog post files to be named according to the following format:

`YEAR-MONTH-DAY-title.MARKUP`

Where `YEAR` is a four-digit number, `MONTH` and `DAY` are both two-digit numbers, and `MARKUP` is the file extension representing the format used in the file. After that, include the necessary front matter. Take a look at the source for this post to get an idea about how it works.

Jekyll also offers powerful support for code snippets:

{% highlight python %}
def print_hi(name)
  print (f"Hi, {name}")

print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
