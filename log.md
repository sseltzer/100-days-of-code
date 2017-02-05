# 100 Days Of Code - Log


### Day 0: December 30, 2016

**Today's Progress:** Started a cleaner boilerplate Node.js app framework with Keystone CMS.

**Thoughts:** My goals are to dive deeper into ES6 and start implementing a more functional style.

**Time:** 2 hrs


### Day 1: January 3, 2017

**Today's Progress:** Started setting up Ubuntu VM for the 100 days. Using and refining my env setup.

**Thoughts:** Networking and configuring Ubuntu can be frustrating. Need a unix based dev machine.

**Time:** 1.5 hrs

**Link(s) to work**
1. [My Gists](https://gist.github.com/sseltzer)


### Day 2: January 4, 2017

**Today's Progress**: Finished configuring Ubuntu for the most part. Environment is set up. Sublime is set up on the host machine for development. Everything is optimal to begin.

**Thoughts:** Ubuntu VMs are a pain. Sudo all the things. Networking doesn't work right still with this NIC, need to investigate.

**Time:** 1 hr


### Day 3: January 5, 2017

**Today's Progress:** Set up my git project from last December and starting to inventory everything for a place to begin.

**Link(s) to work:**
1. [Gladius](https://github.com/sseltzer/gladius)


### January 6, 2017 - sick
### January 7, 2017 - sick
### January 8, 2017 - sick
### January 9, 2017 - sick
### January 10, 2017 - break


### Day 4: January 11, 2017

**Today's Progress:** Not much progress. Created a template Keystone app using the Yeoman generator. Struggling getting it to run on Ubuntu. 

**Thoughts:** I spent hours spinning my wheels this evening. Nothing will compile in this gcc/python setup. Internet not helpful. Left the evening with nothing to show for my work.

**Time:** 3hrs


### Day 5: January 12, 2017

**Today's Progress:** Made a breakthrough. First pass at integrating KSjs is done. Got caught up on my log and such as well.

**Thoughts:** Versioning issues got me. No matter what I did nothing worked. [This link](https://github.com/Automattic/mongoose/issues/2285) lead me to my solution:
```
  rm -rf node_modules/keystone/node_modules/mongodb
  rm -rf node_modules/keystone/node_modules/mongoose
```
Important lesson learned. Sub module dependencies may sometimes be incompatible with your environment, and no matter what you do to your main module, you may still have issues. The solution ultimately was to remove all dependencies and build my own like I was going to to begin with in the final merged product. The Yeoman generator is also out of date for KS (doesn't use the latest Beta) which is a problem for this setup.

**Link(s) to work:**
1. [Gladius KS Initial Commit](https://github.com/sseltzer/gladius/commit/f247cdb71df6fc1baef984b664edbfee848c0f07)

**Time:** 2 hrs


### Day 6: January 13, 2017

**Today's Progress:** Worked on VM configuration. Trying to get network adapters working.

**Thoughts:** 

**Time:** 1hrs


### Day 7: January 14, 2017

**Today's Progress:** Worked on VM configuration. Found a workaround.

**Thoughts:** 

**Time:** 1hrs


### Day 8: January 15, 2017
**Today's Progress:** Docker

### Day 9: January 16, 2017
**Today's Progress:** Docker

### Day 10: January 17, 2017
**Today's Progress:** Docker

### Day 11: January 18, 2017
**Today's Progress:** Docker

### Day 12: January 19, 2017
**Today's Progress:** Docker

### January 20, 2017
**Today's Progress:** Family Day

### Day 13: January 21, 2017
**Today's Progress:** Udemy

### Day 14: January 22, 2017
**Today's Progress:** Docker

### Day 15: January 23, 2017
**Today's Progress:** Docker

### January 24, 2017
**Today's Progress:** Family Day

### January 25, 2017
**Today's Progress:** Family Day

### Day 16: January 26, 2017
**Today's Progress:** Atom

### Day 17: January 27, 2017
**Today's Progress:** Atom

### Day 18: January 28, 2017
**Today's Progress:** Worked on gladius today. Set up gulp and env configs.

**Thoughts:** Not much. Just getting ramped up on setting up my general config. Using a git submodule for the first time. The flat dir structure really helps. This time around everything is much simpler in general.

**Time:** 4hrs

**Link(s) to work:**
1. [Gladius](https://github.com/sseltzer/gladius)

### Day 19: January 29, 2017
**Today's Progress:** Added yarn file. Set up the project to work with heroku. Abstracted more env stuff.

**Thoughts:** Heroku was not intuitive. Especially the port number thing. However, after some issues, I finally got it working right.

**Time:** 6hrs

**Link(s) to work:**
1. [Gladius Heroku](https://sseltzer-gladius.herokuapp.com/)

### Day 20: January 30, 2017

**Today's Progress:** Began adding eslint and customizing atom.

**Time:** 1

### Day 21: January 31, 2017

**Today's Progress:** Finalized lint integration. "npm run lint" will now validate the project. I've also integrated atom-beautify and a few other plugins to ensure that when a file is saved, it will auto format to conform to linting standards.

**Thoughts:** Auto formatting is nice to ensure code conforms to standards with minimal effort. Auto format on save prevented me from having to fix 300+ issues by hand.

**Time:** 2

### Day 22: February 01, 2017

**Today's Progress:** Fixed the last of the lint issues. Everything is clean now.

**Time:** 1

### Day 23: February 02, 2017

**Today's Progress:** Split config file into environment specific configs. Added schema validation for configs. Added some nice error checking and graceful failure with logging when the app detects that it cannot start.

**Thoughts:** Attended a JS meetup to support Jordan and learn about D3 and Node.js debugging. The event was pretty good.

**Time:** 3

### February 03, 2017 - Family day
### February 04, 2017 - Family day

