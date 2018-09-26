---
layout: page
title: Python Setup
root: ..
---

You need to download some files to follow this lesson:

1. Create a repository on github with a name like `LearningPython` or similar.
1. Clone such repository to your desktop using `git clone` as you learnt yesterday.
1. Download [python-novice-inflammation-data.zip][zipdata] and move the file to this folder.
1. Also download [python-novice-inflammation-code.zip][zipcode] and move it to the same folder.
1. If the files aren't unzipped yet, double-click to unzip them. You should end up with 
two new folders called `data` and `code`.
1. To get started, go into the `data` folder from the Unix shell with:

<pre>
$ cd
$ cd Desktop/LearningPython/data
</pre>
{: .source}
   
If you will be using the Jupyter (IPython) notebook for the lesson,
you should have already
[installed Anaconda]({{ page.root }}/#setup)
which includes the notebook.

To start the notebook, open a terminal or git bash and type the command:

<pre>
$ jupyter notebook
</pre>
{: .source}

To start the Python interpreter without the notebook, open a terminal or git bash and type the command:

<pre>
$ python
</pre>
{: .source}

[zipdata]: http://swcarpentry.github.io/python-novice-inflammation/data/python-novice-inflammation-data.zip
[zipcode]: http://swcarpentry.github.io/python-novice-inflammation/code/python-novice-inflammation-code.zip
