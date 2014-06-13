# Contributing
Contributions are welcome and greatly appreciated! 


## Fix typos, grammar, etc.
Create pull requests at 
https://github.com/makaimc/howdoistartup.github.io/pulls.


## Submit feedback
The best way to send feedback is to file an issue at 
https://github.com/makaimc/howdoistartup.github.io/issues.


## Get started
Check out the blog post on 
[Getting Started with Pelican and GitHub Pages](http://www.mattmakai.com/introduction-to-pelican.html) 
if you are not familiar with the 
[Pelican](http://docs.getpelican.com/) static webpage generator.

Ready to contribute? Here is how to set up How Do I Start Up? for local 
development.

1. Fork the [howdoistartup.github.io](https://github.com/makaimc/howdoistartup.github.com) repo on GitHub.

2. Clone your fork locally

    $ git clone git@github.com:your_name_here/howdoistartup.github.io.git hdis

3. Install your local copy into a virtualenv and set up your fork for local development::

    $ virtualenv --no-site-packages venvs/hdis
    $ source venvs/hdis/bin/activate
    $ cd hdis

Note: make changes to the source/content/pages/\*.markdown files then execute a
``make run`` command from the source/ directory.

6. Commit your changes and push your branch to GitHub

    $ git add .
    $ git commit -m "Your detailed description of your changes."
    $ git push origin gh-pages

7. Submit a pull request through the GitHub website.

