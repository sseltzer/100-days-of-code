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

**Time:** X hrs
