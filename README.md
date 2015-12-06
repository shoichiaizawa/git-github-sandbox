git-github-sandbox
==================

This repository does not contain any programming code,
but solely exists for me to be able to play around with git commands
and see how all my actions can affect both local and remote repositories.

I am also planning to use this repository as todo lists
for my projects or general stuff, for now at least I can say.

TODOs
-----

![Eisenhower Matrix](img/eisenhower-box.jpg)

> "I have two kinds of problems, the urgent and the important.
> The urgent are not important, and the important are never urgent."
> -- Dwight D. Eisenhower

I decided to employ the [Eisenhower Method](https://en.wikipedia.org/wiki/Time_management#The_Eisenhower_Method)
to organise my tasks.
I might not use the method as it is supposed to be
but I roughly use this method in a way that I feel comfortable to work on.

Instead of using the four quadrants I use four separate unordered lists.

<sub>For detailed information about the Eisenhower Method read:</sub>

- <sub>http://jamesclear.com/eisenhower-box</sub>

### Eisenhower List

##### TODO-1: Important, Urgent

- [ ] Reply emails
- [ ] Sort contracts

##### TODO-2: Important, Not urgent

- Do meteor tutorials as many as possible:
    - [Official Todo Apps](https://www.meteor.com/learn)
    - [scotch.io](https://scotch.io/?s=meteor)
    - [angular-meteor.com](http://angular-meteor.com/)
    - and more
- [ ] Install some basic npm packages globally for tweaking
    - Install must-have global npm packages; for example:
        - jslint, jshint or eshint; get the best one
        - gulp
        - grunt-cli
        - coffee-script
        - bower
        - browserify
        - nodemon
        - https://github.com/suan/vim-instant-markdown
        - etc
    - I had some npm packages installed with the Homebrew version of Node.js
      -- I deleted everything already TODO: summarise how how to delete Node.js
      and npm from the system;
      these were the global packages installed previously:

        ```
        # Previously I installed these packages
        # when Node.js + npm were installed via Homebrew,
        # and I don't know these should have been installed globally.
        $ npm list -g --depth=0
        /usr/local/lib
        ├── bower@1.6.3
        ├── browserify@11.2.0
        ├── doctoc@0.15.0
        ├── gulp@3.9.0
        ├── javascripting@2.1.0
        ├── npm@3.3.9
        └── ungit@0.9.3
        ```
- Install Vim plug-ins or tweak settings:
    - Markdown related
        - Look into this and find out what this can do:
          https://github.com/plasticboy/vim-markdown
        - And more
    - completion
    - syntax highlighter
        - JavaScript: [JSLint](http://www.jslint.com/)
          vs [JSHint](http://jshint.com/)
          vs [ESLint](http://eslint.org/)
- [ ] Find out how to create a remote repository on GitHub
      from the local terminal
    - This can be done using the [GitHub APIs](https://developer.github.com/v3/)
    - Read the following pages:
        - [Create a Github Repo from the Command Line](https://viget.com/extend/create-a-github-repo-from-the-command-line)
        - [Stack Overflow: Is it possible to create a remote repo on GitHub from the CLI without ssh?](http://stackoverflow.com/questions/2423777/is-it-possible-to-create-a-remote-repo-on-github-from-the-cli-without-ssh)
- Sort emails inside Mailbox.app

##### TODO-3: Not important, Urgent

- [ ] foo
- [ ] bar
- [ ] baz

##### TODO-4: Not important, Not urgent

- [ ] Fix errors on existing jekyll projects
- [ ] Find a decent version control software for design projects
      -- [Pixelapse](https://www.pixelapse.com/)
      looks compelling and its free tier offers unlimited public projects
    - [According to VentureBeat](http://venturebeat.com/2014/06/05/for-designers-version-control-is-a-big-problem-but-github-is-close-to-solving-it/),
      GitHub announced on June 6 2014 that they had started
      supporting PSD viewing and diffing.
      See their [official blog post on June 6 2014](https://github.com/blog/1845-psd-viewing-diffing).
        - Test this above in my test repository
- [ ] Install f.lux on iPhone
- [ ] Read though http://www.codenewbie.org/
- [ ] Look into [karan/joe](https://github.com/karan/joe),
      a gitignore file generator

### Eisenhower Box

TODO: Test if a markdown table can replicate the real Eisenhower Box

<!--
,Urgent,Not Urgent
Important,foo,bar
Not Important,baz,qux
-->

|               | Urgent | Not Urgent |
|---------------|--------|------------|
| **Important** | <ul><li>[ ] Reply emails</li><li>[ ] Sort contracts</li></ul> | <ul><li>Do meteor tutorials</li><li>Install must-have global npm packages</li></ul>        |
| **Not Important** | baz    | qux        |

### TODO-list-1: Some stuff to sort out before 2016 comes

- [ ] Do a clean install the OS X on the new SSD,
      which I bought at the end of April (OMG, I am so lazy...)
    - [ ] Do the OS X provisioning using Ansible
        - My ansible playbook can be executed with `-C`/`--check` option, a dry-run command
        - Enhance the settings
- [ ] Delete unused Mac apps
    - I need to do clean install anyway but it would be nice
      to identify what is important and what is not prior to making the action:
        - [ ] Make sure all the basics stuff is backed up
            - [ ] dotfiles
            - [ ] Contacts
            - [ ] Broseer Bookmarks
            - [ ] Existing emails, just in case
            - [ ] Network info
        - [ ] bar
        - [ ] baz
- [ ] Delete unused iPhone apps
    - My iPhone only has 4.5 GB ish of the remaining disk space,
      which is not a lot. Delete the ones I never use.

### TODO-list-2: What I want to learn in 2016

#### ### Learn, learn, learn

- Do MOOCs courses
    - Coursera:
        - [Stanford University - Machine Learning by Andrew Ng](https://www.coursera.org/learn/machine-learning)
    - edX:
        - [Introduction to Computer Science and Programming Using Python](https://www.edx.org/course/introduction-computer-science-mitx-6-00-1x-6)
          -- starts on **January 13, 2016**
            - I abandoned the last session half way though
              because I chose to stay in the audit mode
              so make sure I pay for the course for a verified track,
              stay motivated and complete the course
    - Other info:
        - [open-source-society/computer-science](https://github.com/open-source-society/computer-science)
          suggests a curriculum with a range of Computer Science courses from various MOOC providers
        - [Replicating a BSc in Computer Science through MOOCs](http://gregorulm.com/replicating-a-bsc-in-computer-science-through-moocs/)
            - [gregorulm/mooc](https://github.com/gregorulm/mooc)
- Lynda courses
    - The thing is I am a premium annual member and have not studied anything
      on Lynda.com for a few months... bammer!
- Many other paid courses
    - I paid for quite many courses, make sure learning from those courses before the technologies they teaching becomes obsolete. Here are some courses I paid for:
        - Udemy courses
        - Makers Cabin

DONEs
-----

### 2015-12-05

- Enroll Coursera Machine Learning course

### 2015-11-13

##### Summary

I was planning to work on the existing jekyll generated blog powered
by jekyll-bootstrap and host it at username.github.io
but in the end I abandoned it.
I changed the name of the repository
and created another repository named username.github.io.

There is no content at this time.
So my next goal about static site blogging is
to wrote blog post in a regular basis.
I was recommended that I should still to a regular publishing plan.
Whether publishing once a day, once in three days or once in a week,
it is important to keep on doing it.

- [x] Air the jekyll blog, with or without a unique domain

Not important but I wanted to do

- [x] Subscribe Meteor newsletter -> answered survey
- [x] Sign up at https://unsplash.com/

### 2015-11-12

##### Summary

As planned I did install Node.js and npm via nvm.
Spending much time on reading about how to install nvm,
I came across some people insisting that
[nvm should not be installed via Homebrew at all](https://github.com/creationix/nvm/issues/469)
(and even saying nvm installation with Homebrew is an unofficial method;
thus one should install nvm only the official way)
but I used Homebrew to install it.

Here are some of the websites/blogs I visited when installing nvm:

- https://www.araport.org/docs/science-apps-configuring-development-environment/installing-nodejs
- http://stackoverflow.com/questions/28017374/what-is-the-suggested-way-to-install-brew-node-js-io-js-nvm-npm-on-os-x
- http://sourabhbajaj.com/mac-setup/Node.js/README.html

##### Original TODOs

- [x] Install Node.js via brew, nvm, n, nodebrew, or others
    - I would probably go with nvm as it has the most stars on GitHub
      among other Node.js version managers.
      Also nvm seems the most active on GitHub
    - Numbers of stars for each project (as of 2015-11-12):
        - [creationix/nvm](https://github.com/creationix/nvm) -- 9168 stars
        - [tj/n](https://github.com/tj/n) -- 3252 stars
        - [hokaccha/nodebrew](https://github.com/hokaccha/nodebrew) -- 459 stars
    - Install npm -- npm is automatically comes
      with a Node.js installation unless you exclude it

Notes
-----

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
[How to Write a Git Commit Message](http://chris.beams.io/posts/git-commit/)
for details.

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

### GitHub Flavored Markdown (GFM)

- [GitHub Flavored Markdown](https://help.github.com/articles/github-flavored-markdown/)

### Create a remote repository on GitHub from the local terminal

TODO: I have not tested this tweak yet.

- [Create a Github Repo from the Command Line](https://viget.com/extend/create-a-github-repo-from-the-command-line)
- [Stack Overflow: Is it possible to create a remote repo on GitHub from the CLI without ssh?](http://stackoverflow.com/questions/2423777/is-it-possible-to-create-a-remote-repo-on-github-from-the-cli-without-ssh)

`$ git config --global github.user GITHUB_USERNAME`

Jekyll and other static site generators
---------------------------------------

- [Jekyll powered sites (from Jekyll GitHub Wiki)](https://github.com/jekyll/jekyll/wiki/sites)
  -- a list of sites powered by Jekyll

LICENSES information
--------------------

> Get familiarised with Licenses

For code:

- MIT License
- Apache License
- GPL (V2 or V3)
- more

Non-code:

- Creative Commons
- etc

References:

- [choosealicense.com](http://choosealicense.com/)
  -- this is created by GitHub, thanks to Jessica Lord for sharing this!
- [github/choosealicense.com](https://github.com/github/choosealicense.com)
  -- the GitHub repository of the website

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

Machine Learning
----------------

- [Stanford University - Machine Learning by Andrew Ng](https://www.coursera.org/learn/machine-learning)
  - Do this for the session beginning on 30th November! ~~Enroll by 5th December!~~ -> Paid on 5th December
- [hangtwenty/dive-into-machine-learning](https://github.com/hangtwenty/dive-into-machine-learning)

