git-github-sandbox
==================

This repository does not contain any programming code, but solely exists for me
to be able to play around with git commands and see how all my actions can
affect both local and remote repositories.

I am also planning to use this repository as todo lists for my projects or
general stuff, for now at least I can say.

--------------------------------------------------------------------------------

TODOs
=====

![Eisenhower Matrix](img/eisenhower-box.jpg)

> "I have two kinds of problems, the urgent and the important.
> The urgent are not important, and the important are never urgent."
> -- Dwight D. Eisenhower

I decided to employ the [Eisenhower
Method](https://en.wikipedia.org/wiki/Time_management#The_Eisenhower_Method) to
organise my tasks. I might not use the method as it is supposed to be but I
roughly use this method in a way that I feel comfortable to work on.

~~Instead of using the four quadrants I use four separate unordered lists.~~

<sub>For detailed information about the Eisenhower Method read:</sub>

- <sub>http://jamesclear.com/eisenhower-box</sub>

Eisenhower Box
--------------

For an organisational purpose, instead of using a Markdown table, I used HTML
code to create this four quadrant box.

<!-- |                   | Urgent | Not Urgent | -->
<!-- |-------------------|--------|------------| -->
<!-- | **Important**     | foo    | bar        | -->
<!-- | **Not Important** | baz    | qux        | -->

<table>
  <colgroup>
    <col style="text-align:left;"/>
    <col style="text-align:left;"/>
    <col style="text-align:left;"/>
  </colgroup>

  <thead>
    <tr>
      <th style="text-align:left;"></th>
      <th style="text-align:left;">Urgent</th>
      <th style="text-align:left;">Not Urgent</th>
    </tr>
  </thead>

  <tbody>
    <tr>
      <td style="text-align:left;"><strong>Important</strong></td>
      <td style="text-align:left;">
      <!-- Important, Urgent -->
        <li><input type="checkbox">Sort contracts</li>
      </td>
      <td style="text-align:left;">
      <!-- Important, Not Urgent -->
        <li>Do meteor tutorials as many as possible:</li>
          <ul>
            <li>[official todo apps](https://www.meteor.com/learn)</li>
            <li>[scotch.io](https://scotch.io/?s=meteor)</li>
            <li>[angular-meteor.com](http://angular-meteor.com/)</li>
          </ul>
        <li><input type="checkbox">Install some basic npm packages globally for tweaking</li>
          <ul>
            <li>Install must-have global npm packages; for example:</li>
              <ul>
                <li>jslint, jshint or eshint; get the best one</li>
                <li>gulp</li>
                <li>grunt-cli</li>
                <li>coffee-script</li>
                <li>bower</li>
                <li>browserify</li>
                <li>nodemon</li>
                <li>https://github.com/suan/vim-instant-markdown</li>
                <li>etc</li>
              </ul>
          </ul>
        <li>Install Vim plug-ins or tweak settings:</li>
          <ul>
            <li>Markdown related:</li>
              <ul>
                <li>Find out how to do LaTeX writing compatible for GitHub Flavoured Markdown</li>
              </ul>
            <li>Completion</li>
            <li>Syntax checkers</li>
            <li>JavaScript: [JSLint](http://www.jslint.com/) vs [JSHint](http://jshint.com/) vs [ESLint](http://eslint.org/)</li>
          </ul>
        <li><input type="checkbox">Find out how to create a remote repository on GitHub from the local terminal</li>
        <li>Sort emails inside Mailbox.app</li>
        <li><input type="checkbox">Delete unused Mac apps</li>
        <li><input type="checkbox">Delete unused iPhone apps</li>
      </td>
    </tr>
    <tr>
      <td style="text-align:left;"><strong>Not Important</strong></td>
      <td style="text-align:left;">
      <!-- Not important, Urgent -->
        <!-- <li>foo</li> -->
        <!-- <li>bar</li> -->
        <!-- <li>baz</li> -->
      </td>
      <td style="text-align:left;">
      <!-- Not important, Not Urgent -->
        <li><input type="checkbox">Fix errors on existing jekyll projects</li>
        <li><input type="checkbox">Test [PSD viewing and diffing](https://github.com/blog/1845-psd-viewing-diffing) in this test repository</li>
        <li><input type="checkbox">Install f.lux on iPhone</li>
        <li><input type="checkbox">Read though http://www.codenewbie.org/</li>
        <li><input type="checkbox">Look into [karan/joe](https://github.com/karan/joe), a gitignore file generator</li>
      </td>
    </tr>
  </tbody>
</table>

TODO-list-1: What I want to do in 2016
--------------------------------------

### Mac OS X refreshment

- [ ] Do a clean install the OS X on the new SSD -- do this as soon as I am done with Coursera Machine Learning Course
    - [ ] Make sure all the basics stuff is backed up
        - [ ] dotfiles
        - [ ] Contacts
        - [ ] Browser Bookmarks
        - [ ] Existing emails, just in case
        - [ ] Network info
        - [ ] BetterTouchTool settings
        - [ ] keychain Access items
        - [ ] Dash backup
    - [ ] Do the OS X provisioning using Ansible
        - My ansible playbook can be executed with `-C`/`--check` option, a dry-run command
        - [ ] Now enhance the settings

### Learn, learn, learn

- Do MOOCs courses
    - Coursera:
    - edX:
        - [Introduction to Computer Science and Programming Using Python](https://www.edx.org/course/introduction-computer-science-mitx-6-00-1x-6) -- starts on **January 13, 2016**
    - Other info:
        - [open-source-society/computer-science](https://github.com/open-source-society/computer-science) suggests a curriculum with a range of Computer Science courses from various MOOC providers
        - [Replicating a BSc in Computer Science through MOOCs](http://gregorulm.com/replicating-a-bsc-in-computer-science-through-moocs/)
            - [gregorulm/mooc](https://github.com/gregorulm/mooc)
- Lynda courses
- Many other paid courses
    - Udemy courses
    - Makers Cabin

DONEs
-----

### 2015-12-09

- [x] Install [plasticboy/vim-markdown](https://github.com/plasticboy/vim-markdown)

### 2015-12-05

- [x] Enroll [Coursera Machine Learning course](https://www.coursera.org/learn/machine-learning)

### 2015-11-15

- [x] Find a decent version control software for design projects
      -- [Pixelapse](https://www.pixelapse.com/) looks compelling and its free tier offers unlimited public projects
    - [According to VentureBeat](http://venturebeat.com/2014/06/05/for-designers-version-control-is-a-big-problem-but-github-is-close-to-solving-it/), GitHub announced on June 6 2014 that they had started supporting PSD viewing and diffing. See their [official blog post on June 6 2014](https://github.com/blog/1845-psd-viewing-diffing).

### 2015-11-13

##### Summary

I was planning to work on the existing jekyll generated blog powered by
jekyll-bootstrap and host it at username.github.io but in the end I abandoned
it. I changed the name of the repository and created another repository named
username.github.io.

There is no content at this time. So my next goal about static site blogging is
to wrote blog post in a regular basis. I was recommended that I should still to
a regular publishing plan. Whether publishing once a day, once in three days or
once in a week, it is important to keep on doing it.

- [x] Air the jekyll blog, with or without a unique domain

Not important but I wanted to do

- [x] Subscribe Meteor newsletter -> answered survey
- [x] Sign up at https://unsplash.com/

### 2015-11-12

##### Summary

As planned I did install Node.js and npm via nvm. Spending much time on reading
about how to install nvm, I came across some people insisting that [nvm should
not be installed via Homebrew at
all](https://github.com/creationix/nvm/issues/469) (and even saying nvm
installation with Homebrew is an unofficial method; thus one should install nvm
only the official way) but I used Homebrew to install it.

Here are some of the websites/blogs I visited when installing nvm:

- https://www.araport.org/docs/science-apps-configuring-development-environment/installing-nodejs
- http://stackoverflow.com/questions/28017374/what-is-the-suggested-way-to-install-brew-node-js-io-js-nvm-npm-on-os-x
- http://sourabhbajaj.com/mac-setup/Node.js/README.html

##### Original TODOs

- [x] Install Node.js via brew, nvm, n, nodebrew, or others
    - I would probably go with nvm as it has the most stars on GitHub among other Node.js version managers. Also nvm seems the most active on GitHub
    - Numbers of stars for each project (as of 2015-11-12):
        - [creationix/nvm](https://github.com/creationix/nvm) -- 9168 stars
        - [tj/n](https://github.com/tj/n) -- 3252 stars
        - [hokaccha/nodebrew](https://github.com/hokaccha/nodebrew) -- 459 stars
    - Install npm -- npm is automatically comes with a Node.js installation unless you exclude it

--------------------------------------------------------------------------------

Notes
=====

Git and GitHub
--------------

### `git commit`

#### The seven rules of a great git commit message

1. Separate subject from body with a blank line
2. Limit the subject line to 50 characters
3. Capitalize the subject line
4. Do not end the subject line with a period
5. Use the imperative mood in the subject line
6. Wrap the body at 72 characters
7. Use the body to explain what and why vs. how

```
Summarize changes in around 50 characters or less

More detailed explanatory text, if necessary. Wrap it to about 72
characters or so. In some contexts, the first line is treated as the
subject of the commit and the rest of the text as the body. The
blank line separating the summary from the body is critical (unless
you omit the body entirely); various tools like `log`, `shortlog`
and `rebase` can get confused if you run the two together.

Explain the problem that this commit is solving. Focus on why you
are making this change as opposed to how (the code explains that).
Are there side effects or other unintuitive consequenses of this
change? Here's the place to explain them.

Further paragraphs come after blank lines.

 - Bullet points are okay, too

 - Typically a hyphen or asterisk is used for the bullet, preceded
   by a single space, with blank lines in between, but conventions
   vary here

If you use an issue tracker, put references to them at the bottom,
like this:

Resolves: #123
See also: #456, #789
```

See the blog post:
[How to Write a Git Commit Message](http://chris.beams.io/posts/git-commit/) for details.

Other readings relating to Git commit messaging:

- [A Note About Git Commit Messages -- Tim Pope](http://tbaggery.com/2008/04/19/a-note-about-git-commit-messages.html)
- [Commit messages - Good practices -- SlideShare](http://www.slideshare.net/TarinGamberini/commit-messages-goodpractices)
- [A bad commit message example](http://stopwritingramblingcommitmessages.com/)

### `git remote`

- [Renaming a remote](https://help.github.com/articles/renaming-a-remote/)
- [Renaming a repository](https://help.github.com/articles/renaming-a-repository/)

### Understanding the GitHub Flow

> GitHub Flow is a lightweight, branch-based workflow that supports teams
> and projects where deployments are made regularly.
> This guide explains how and why GitHub Flow works.

See: https://guides.github.com/introduction/flow/index.html

### Work around how to combine one repository to another

#### `submodule` vs `subtree`

- [Stack Overflow: How do you merge two git repositories?](http://stackoverflow.com/questions/1425892/how-do-you-merge-two-git-repositories)
- [Stack Overflow: How do I work with a git repository within another repository?](http://stackoverflow.com/questions/1811730/how-do-i-work-with-a-git-repository-within-another-repository)
- [Stack Overflow: Detach subdirectory into separate Git repository](http://stackoverflow.com/questions/359424/detach-subdirectory-into-separate-git-repository)
- [7.11 Git Tools - Submodules](http://git-scm.com/book/en/v2/Git-Tools-Submodules)
- [6.7 Git Tools - Subtree Merging](http://git-scm.com/book/en/v1/Git-Tools-Subtree-Merging)
- [Subtree merging and you](http://nuclearsquid.com/writings/subtree-merging-and-you/)
- [About Git subtree merges](https://help.github.com/articles/about-git-subtree-merges/)
- [Alternatives To Git Submodule: Git Subtree](http://blogs.atlassian.com/2013/05/alternatives-to-git-submodule-git-subtree/)
- [The power of Git subtree](https://developer.atlassian.com/blog/2015/05/the-power-of-git-subtree/)

### `git rebase`

- [About Git rebase](https://help.github.com/articles/about-git-rebase/)

### GitHub fork

- [Fork A Repo](https://help.github.com/articles/fork-a-repo/)
- [Syncing a fork](https://help.github.com/articles/syncing-a-fork/)
- [octocat/Spoon-Knife](https://github.com/octocat/Spoon-Knife)

### GitHub Flavored Markdown (GFM)

- [GitHub Flavored Markdown](https://help.github.com/articles/github-flavored-markdown/)

### Create a remote repository on GitHub from the local terminal

- [Create a Github Repo from the Command Line](https://viget.com/extend/create-a-github-repo-from-the-command-line)
- [Stack Overflow: Is it possible to create a remote repo on GitHub from the CLI without ssh?](http://stackoverflow.com/questions/2423777/is-it-possible-to-create-a-remote-repo-on-github-from-the-cli-without-ssh)

`$ git config --global github.user GITHUB_USERNAME`

Programming naming convention
-----------------------------

- [What's the name for hyphen-separated case? \[closed\]](http://stackoverflow.com/questions/11273282/whats-the-name-for-hyphen-separated-case) -- Stack Overflow
- [Naming convention (programming)](https://en.wikipedia.org/wiki/Naming_convention_(programming)) -- Wikipedia
- [Letter cases -- Special case styles](https://en.wikipedia.org/wiki/Letter_case#Special_case_styles) -- Wikipedia
    - [\[C/c\]amelCase](http://c2.com/cgi/wiki?CamelCase) -- Cunningham & Cunningham's WikiWikiWeb
    - [PascalCase](http://c2.com/cgi/wiki?PascalCase)
    - [kebab-case](http://c2.com/cgi/wiki?KebabCase)

Jekyll and other static site generators
---------------------------------------

### Jekyll

- [jekyllthemes.org](http://jekyllthemes.org/)
    - [mattvh/jekyllthemes](https://github.com/mattvh/jekyllthemes/) -- A directory of the best-looking themes for Jekyll blogs http://jekyllthemes.org/
- [Jekyll powered sites (from Jekyll GitHub Wiki)](https://github.com/jekyll/jekyll/wiki/sites) -- a list of sites powered by Jekyll

### Static site generators

- [StaticGen](https://www.staticgen.com/)
    - [netlify/staticgen](https://github.com/netlify/staticgen) -- StaticGen.com, A leaderboard of top open-source static site generators http://www.staticgen.com
- [staticsitegenerators.net](https://staticsitegenerators.net/) -- The definitive listing of Static Site Generators — all 412 of them!
    - [bevry/staticsitegenerators-website](https://github.com/bevry/staticsitegenerators-website) -- Website containing the complete listing of static site generators http://staticsitegenerators.net

LICENSES information
--------------------

> Get familiarised with Licenses

### For code:

- MIT License:
    - [MIT License -- choosealicense.com](http://choosealicense.com/licenses/mit/)
    - [The MIT License (MIT) -- Open Source Initiative](https://opensource.org/licenses/MIT)
    - [MIT License -- Wikipedia](https://en.wikipedia.org/wiki/MIT_License)
- Apache License:
    - [Appach Lisense 2.0 -- choosealicense.com](http://choosealicense.com/licenses/apache-2.0/)
    - [Apache License, Version 2.0 -- Open Source Initiative](https://opensource.org/licenses/Apache-2.0)
    - [Appach Lisense -- Wikipedia](https://en.wikipedia.org/wiki/Apache_License)
- [GNU GPL (V2 or V3)](https://en.wikipedia.org/wiki/GNU_General_Public_License):
    - GNU GPLv2:
        - [GNU General Public License v2.0 -- choosealicense.com](http://choosealicense.com/licenses/gpl-2.0/)
        - [GNU General Public License, version 2 (GPL-2.0) -- Open Source Initiative](https://opensource.org/licenses/GPL-2.0)
        - [GNU General Public License, version 2 -- www.gnu.org](http://www.gnu.org/licenses/old-licenses/gpl-2.0.en.html)
    - GNU GPLv3:
        - [GNU General Public License v3.0 -- choosealicense.com](http://choosealicense.com/licenses/gpl-3.0/)
        - [GNU General Public License, version 3 (GPL-3.0) -- Open Source Initiative](https://opensource.org/licenses/GPL-3.0)
        - [GNU General Public License -- www.gnu.org](http://www.gnu.org/licenses/gpl.html)
- Other licenses:
    - [Other licenses -- choosealicense.com](http://choosealicense.com/licenses/)
    - [Licenses by Name -- Open Source Initiative](https://opensource.org/licenses/alphabetical)
    - [Comparison of free and open-source software licenses -- Wikipedia](https://en.wikipedia.org/wiki/Comparison_of_free_and_open-source_software_licenses)

### Non-code:

- [Creative Commons -- creativecommons.org](http://creativecommons.org/choose/)
- [Creative Commons -- Wikipedia](https://en.wikipedia.org/wiki/Creative_Commons)

### No License:

- [No License -- choosealicense.com](http://chooseali)
- [License-free software -- Wikipedia](https://en.wikipedia.org/wiki/License-free_software)

##### References:

- [choosealicense.com](http://choosealicense.com/) -- this is created by GitHub, thanks to Jessica Lord for sharing this!
    - [github/choosealicense.com](https://github.com/github/choosealicense.com) -- the GitHub repository of the website

Vim
---

### tpope/vim-surround

Example usage presented in README of `tpope/vim-surround`

```
Initial state   =>  "Hello World!"
cs"'            =>  'Hello World!'
cs'<q>          =>  <q>Hello World!</q>
cst"            =>  "Hello World!"
ds"             =>  Hello World!
ysiw]           =>  [Hello] World!
cs]{            =>  { Hello } World!
yssb or yss)    =>  ({ Hello } World!)
ds{ds)          =>  Hello World!
ysiw<em>        =>  <em>Hello</em> World!

V-LINE and S>p class="important"

<p class="important">
  <em>Hello</em> World!
</p>
```

Machine Learning, Neural Networks, Deep Learning
------------------------------------------------

TODO: Sort list items for better readability

Some of Machine Learning, Neural Networks, Deep Learning resources collected on
the internet I found interesting are listed below.

### MOOCs (listed: courses, learning resources)

- [Coursera: Stanford University - Machine Learning by Andrew Ng](https://www.coursera.org/learn/machine-learning)
- [Udacity: Deep Learning by Vincent Vanhoucke from Google](https://www.udacity.com/course/deep-learning--ud730)
- [Machine learning courses online](http://fastml.com/machine-learning-courses-online/)

### Readings (listed: learning resources)

- [7 Steps to Mastering Machine Learning With Python](http://www.kdnuggets.com/2015/11/seven-steps-machine-learning-python.html)
- [Deep Learning is Easy - Learn Something Harder](http://www.inference.vc/deep-learning-is-easy/)

### GitHub repositories (listed: learning resources, notes, libraries, frameworks)

#### Learning Resources:

- [hangtwenty/dive-into-machine-learning](https://github.com/hangtwenty/dive-into-machine-learning) -- Dive into Machine Learning with Python Jupyter notebook and scikit-learn http://hangtwenty.github.io/dive-into-machine-learning
- [donnemartin/data-science-ipython-notebooks](https://github.com/donnemartin/data-science-ipython-notebooks) -- Continually updated data science Python notebooks: Spark, Hadoop MapReduce, HDFS, Kaggle, deep learning (TensorFlow, Theano, Caffe), scikit-learn, matplotlib, pandas, NumPy, SciPy, AWS, and various command lines. https://bit.ly/data-notes
- [josephmisiti/awesome-machine-learning](https://github.com/josephmisiti/awesome-machine-learning?utm_source=hackernewsletter&utm_medium=email&utm_term=learn) -- A curated list of awesome Machine Learning frameworks, libraries and software.
- [johnmyleswhite/ML_for_Hackers](https://github.com/johnmyleswhite/ML_for_Hackers) -- Code accompanying the book "Machine Learning for Hackers" http://shop.oreilly.com/product/0636920018483.do

#### Libraries and Frameworks:

- [tensorflow/tensorflow](https://github.com/tensorflow/tensorflow) -- Computation using data flow graphs for scalable machine learning http://tensorflow.org
- [PredictionIO/PredictionIO](https://github.com/PredictionIO/PredictionIO) -- PredictionIO, a machine learning server for developers and ML engineers. Built on Apache Spark, HBase and Spray. http://prediction.io/
- [BVLC/caffe](https://github.com/BVLC/caffe) -- Caffe: a fast open framework for deep learning. http://caffe.berkeleyvision.org/
- [google/deepdream](https://github.com/google/deepdream) -- No description or website provided.
    - DeepDream is a computer vision program created by Google which uses a convolutional neural network to find and enhance patterns in images via algorithmic pareidolia, thus creating a dreamlike hallucinogenic appearance in the deliberately over-processed images. -- [Wikipedia](https://en.wikipedia.org/wiki/DeepDream)
- [dmlc/mxnet](https://github.com/dmlc/mxnet) -- Lightweight, Portable, Flexible Distributed/Mobile Deep Learning with Dynamic, Mutation-aware Dataflow Dep Scheduler; for Python, R, Julia, Go, Javascript and more http://mxnet.rtfd.org
- [dmlc/xgboost](https://github.com/dmlc/xgboost) -- Scalable, Portable and Distributed Gradient Boosting (GBDT, GBRT or GBM) Library, for Python, R, Java, C++ and more
- [pfnet/chainer](https://github.com/pfnet/chainer) -- A flexible framework of neural networks for deep learning http://chainer.org
- [autumnai/leaf](https://github.com/autumnai/leaf) -- Open Machine Intelligence Framework http://autumnai.github.io/leaf

#### Face recognition

- [cmusatyalab/openface](https://github.com/cmusatyalab/openface) -- Face recognition with deep neural networks. http://cmusatyalab.github.io/openface/

#### Some interesting projects

- [jcjohnson/neural-style](https://github.com/jcjohnson/neural-style) -- Torch implementation of neural style algorithm
- [JuanPotato/Legofy](https://github.com/JuanPotato/Legofy) -- Make images look as if they are made out of 1x1 LEGO blocks
- [ryankiros/neural-storyteller](https://github.com/ryankiros/neural-storyteller) -- A recurrent neural network for generating little stories about images

#### Python

- [scikit-learn/scikit-learn](https://github.com/scikit-learn/scikit-learn) -- scikit-learn: machine learning in Python http://scikit-learn.org
- [clips/pattern](https://github.com/clips/pattern) -- Web mining module for Python, with tools for scraping, natural language processing, machine learning, network analysis and visualization. http://www.clips.ua.ac.be/pages/pattern
- [karpathy/neuraltalk](https://github.com/karpathy/neuraltalk) -- NeuralTalk is a Python+numpy project for learning Multimodal Recurrent Neural Networks that describe images with sentences.
- [karpathy/neuraltalk2](https://github.com/karpathy/neuraltalk2) -- Efficient Image Captioning code in Torch, runs on GPU

#### JavaScript

- [karpathy/convnetjs](https://github.com/karpathy/convnetjs) -- Deep Learning in Javascript. Train Convolutional Neural Networks (or ordinary ones) in your browser.

#### Go

- [sjwhitworth/golearn](https://github.com/sjwhitworth/golearn) -- Machine Learning for Go

#### TODO: Something:

- [numenta/nupic](https://github.com/numenta/nupic) -- Numenta Platform for Intelligent Computing: a brain-inspired machine intelligence platform, and biologically accurate neural network based on cortical learning algorithms. http://numenta.org/
- [JohnLangford/vowpal_wabbit](https://github.com/JohnLangford/vowpal_wabbit) -- Vowpal Wabbit is a machine learning system which pushes the frontier of machine learning with techniques such as online, hashing, allreduce, reductions, learning2search, active, and interactive learning. http://hunch.net/~vw/

