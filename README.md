git-test-repo
=============

A repository does not do anything but just exists for me to be able to practise git commands and see how all my actions can affect both local and remote.

I am also planning to use this repository as my todo lists for my projects or general stuff, for now at least I can say.

TODOs
-----

### TODO-1: Creating simple Meteor apps for people

Recently I came up with the Meteor JavaScript framework and I am in an excitement.

A few weeks back, when I was watching a Japanese Node.js advocate doing one of the Meteor official tutorials while live-coding at live.nicovideo.jp.
I, for some reason, was inspired by what he does with this JavaScript framework with a catchy name – Meteor! How cool is that :D
Not so long later than that day, I stared doing one of the tutorials at https://www.meteor.com/install and you know what happened? I instantly fell in love with it! It was a very fun experience for me to work on the tutorial. Seeing my app going on live on the Meteor's free testing server was a truly pleasant experience.

As of November 2015, I still do not know how to write HTML/CSS nor any programming language properly but this Meteor thing has really been captivating me.
The official tutorial offers three simple todo apps, the first one which I did only requires HTML/CSS and JavaScript. The second one and the third one are also simple todo apps but you create apps combining AngularJS and React -- I will do these two once I find my spare time slot.

So now what? I am thinking about making a web application using Meteor.

Thankfully I came up with some chances which I may be able to apply this technology. Since I am an absolute beginner, obviously the learning curve is very high and not sure if this is manageable with my current skill levels. But within a month, by an end-of-year party with gym mates, I will try to approach the solution as hard as I can.

Here are the two Meteor app ideas:

1. **A simple bingo game app**
  - this may be helpful to my gym mates at an end-of-year party
  - this may not be necessary but I would like to challenge myself to create a simple bingo game app that can be used for the game to win a present
  - details to be added
2. **A topic generator app**
  - this app is to help out participants of a language exchange meetup
  - an app similar to TableTopics
  - Mr Yuki Sakakibara often thinks it would be nice to have an app like this to save people at each table from not being able to find topics to talk about
  - details to be added

I am going to add detailed TODOs for each app soon.

I am also going to list up my working plan for the projects, especially the bingo game app.

### TODO-2: Some stuff to sort out before 2016 comes

- [ ] Do a clean install the OS X on the SSD, which I bought at the end of April (OMG, I am so lazy...)
    - [ ] foo
    - [ ] bar
    - [ ] baz
- [ ] Delete unused iPhone apps
- [ ] Air the jekyll blog, with or without a unique domain

### TODO-3: Some random tasks to do

- [ ] install some basic global packages for tweaking
    - I had some packages installed with the Homebrew version of Node.js -- this was deleted already TODO: summarise how how to delete Node.js and npm from the system
    - these were the global packages installed previously:

        ```
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

    - find out what else is good to be installed globally
        - Some says these packages should be installed
            - coffee-script
            - grunt-cli
- [ ] fix errors on existing jekyll projects
- [ ] foo
- [ ] bar
- [ ] baz

DID
---

### 2015-11-12

Summary: As planned I did install Node.js and npm via nvm. Spending much time on reading about how to install nvm, I came across some people insisting that [nvm should not be installed via Homebrew at all](https://github.com/creationix/nvm/issues/469) (and even saying nvm installation with Homebrew is an unofficial method; thus one should install nvm only the official way) but I used Homebrew to install it.

Here are some of the websites/blogs I visited when installing nvm:

- https://www.araport.org/docs/science-apps-configuring-development-environment/installing-nodejs
- http://stackoverflow.com/questions/28017374/what-is-the-suggested-way-to-install-brew-node-js-io-js-nvm-npm-on-os-x
- http://sourabhbajaj.com/mac-setup/Node.js/README.html

##### TODOs done

- [x] install Node.js via brew, nvm, n, nodebrew, or others
    - I would probably go with nvm as it has the most stars on GitHub among other Node.js version managers. Also nvm seems the most active on GitHub
    - Numbers of stars for each project (as of 2015-11-12):
        - [creationix/nvm](https://github.com/creationix/nvm) -- 9168 stars
        - [tj/n](https://github.com/tj/n) -- 3252 stars
        - [hokaccha/nodebrew](https://github.com/hokaccha/nodebrew) -- 459 stars
    - install npm -- npm is automatically comes with a Node.js installation unless you exclude it

Notes
-----

### The seven rules of a great git commit message

1. Separate subject from body with a blank line
2. Limit the subject line to 50 characters
3. Capitalize the subject line
4. Do not end the subject line with a period
5. Use the imperative mood in the subject line
6. Wrap the body at 72 characters
7. Use the body to explain what and why vs. how

See the blog post: [How to Write a Git Commit Message](http://chris.beams.io/posts/git-commit/) for details.

Other readings relating to Git commit messaging:

- [A Note About Git Commit Messages -- Tim Pope](http://tbaggery.com/2008/04/19/a-note-about-git-commit-messages.html)
- [Commit messages - Good practices -- SlideShare](http://www.slideshare.net/TarinGamberini/commit-messages-goodpractices)
- [A bad commit message example](http://stopwritingramblingcommitmessages.com/)
