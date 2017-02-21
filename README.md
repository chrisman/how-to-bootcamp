# How To Bootcamp

Here are some tips and suggestions I have for how get organized and be effecient in a coding bootcamp.

## Mental and Physical Health

1. Get away and go outside for lunch. Take a walk.

2. Take many small mental breaks throughout the day. Keep a pomodoro timer like [marinara timer](http://www.marinaratimer.com/) open in your browser to remind you to take a small break every 30 minutes or so.

3. Start each day with a warm up instead of diving back into what you were working on. My favorite was [exercism](http://exercism.io/)

4. Try not to ever be stuck on any one thing for more than 30 minutes. If you suddenly realize it's been 45 - 60 minutes, _stop immediately_ and ask for help. Ask classmates, teachers, slack, mentors, etc. If none of those are available, just stop and work on something else for a bit.

3. It may sound funny, but I swear putting on a pair of headphones and listening to soma.fm boosts my productivity 50%.
  * [space station](http://somafm.com/player/#/now-playing/spacestation)
  * [secret agent](http://somafm.com/player/#/now-playing/secretagent)

3. No coding before bed. I remember during stressful projects coding right up till I couldn't stay awake any longer, and then having stressful code dreams all night, and waking up feeling unrested and even more stressed. Give yourself a 'code freeze' an hour or more before bed, and do something to clear your mind. Yoga and a cup of tea. Something to relax and calm your mind.

## Class and People and Human Resources

* Taking notes vs. Class participation. I tried a couple note-taking methods, including paper and pen and Evernote, but eventually stopped trying to take notes altogether, and instead used my time in class actively listening, coding along with the lecture and examples, and asking questions. I found I grasped concepts better that way, and could use time outside lectures to repeat and recreate and apply those concepts in order to reinforce them.

* Your classmates and TAs and instructors are big assets. Use them and talk to them. They'll be your support group during the program, and your network afterward while you're looking for a job.

* Meetups. Go to a meetup once a week or so. You can live off the free pizza and beer, and you'll meet people who are established in the industry, and also new people who are in the same boat as you are. In my experience, the meetup scene is very welcoming to beginners and newbies. Don't be afraid of semming like you don't belong. It's kind of like coding: just start doing it, and then you're a coder! Just go to a meetup, and then you're someone who goes to meetups!
  A couple of especially friendly meetups I've been to:
  * [HTML5 User Group](https://www.meetup.com/HTML5-Denver-Users-Group/)
  * [DenverScrip](https://www.meetup.com/DenverScript/)
  * [RefreshDenver](https://www.meetup.com/refreshdenver/) - Designers and Developers!
  * [Ember.js](https://www.meetup.com/Ember-js-Denver/) - Still have yet to actually _use_ Ember ever, but the community is just so awesome.

* Slack. Participate in [Denver-Devs](https://denverdevs.org/). Get to know your neighbors!
  * General conversation: join #topic-todayi to talk about and celebrate small victories and accomplishments, not necessarily code related.
  * Meet people: Join #topic-lunches to get in on lunch outings. Join #meet-n-greet to be paired up with somebody random for a coffee date.

## Jobs and Resumes and Marketing and Networking

* Make a portfolio website. Github offers [free hosting](https://pages.github.com/). Buy a cheap domain to point to it. It's okay to start putting stuff in your portfolio right now. It'll chart your progress and growth.

* Consider blogging, even if just for yourself. It'll help you organize and articulate your thoughts. A 'Week In Review' post each week will help you keep track of what you know.

* Reach out to people on LinkedIn. I used to cold contact whoever had the equivelant title of "VP of Tech" at companies I was interested in and ask them out for a cup of coffee. Most people were surprisingly receptive to this. Especially if you frame the conversation as "I'm new to the industry and would like to hear about what you do and how you got started, and whether you have any advice for somebody just getting started."

## Terminal

2. [Command Line Mysteries](https://github.com/veltman/clmystery) - Learn some commandline utilities.

1. [ohmyzsh](http://ohmyz.sh/) - framework for the zsh shell. If for nothing else, worth it for the github plugins. Alternately, try [bash-it](https://github.com/Bash-it/bash-it).

2. [diff so fancy](https://github.com/so-fancy/diff-so-fancy) makes `git diff` a little more pleasant to read.

3. [the silver searcher](https://github.com/ggreer/the_silver_searcher). use `ag` to quickly search your project

## Atom/Text Editors

__General__

From _[Seven habits of effective text editing](http://www.moolenaar.net/habits.html)_ by the author of vim:

> There are three basic steps:
> 
> 1. While you are editing, keep an eye out for actions you repeat and/or spend quite a bit of time on.
> 2. Find out if there is an editor command that will do this action quicker. Read the documentation, ask a friend, or look at how others do this.
> 3. Train using the command. Do this until your fingers type it without thinking.

Invest in learning to type less. Learn shortcuts and use them relentlessly.

__Atom Plugins__

I didn't use Atom that much for that long. But here are a few plugins I remember liking. (Go to _Settings_ and _Install_ to search for and install packages.)

* atom-beautify - fix indenting/format your file
* color-picker - quick access to a color picker
* [emmet](http://docs.emmet.io/cheat-sheet/) - powerful HTML expansion
* minimap - tiny little map of your whole file
* pigmets - highlight colors in your CSS.

## Other Tools and Programs

On tools in general, set aside up to an hour a week to do nothing but investigate and more deeply learn your tools. Learn a new keyboard shortcut for your text editor or browser, and commit to incorporating that into your workflow.

2. Learn [Chrome Dev Tools](https://developers.google.com/web/tools/chrome-devtools/).

1. [Spectacle](https://www.spectacleapp.com/) - window management for MacOS

2. [flux](https://justgetflux.com/) - don't burn out your retinas

3. [Sip](http://sipapp.io/) - color picker

4. [screenhero](https://screenhero.com/) - for screensharing. many a late night debugging session was done over screenhero.

## CSS

Naming things is hard. Pick a CSS methodology like [BEM] or [Suit] and try it out. It will at least give you a different vocabulary with which to think about and organize your project.

Other resources:

* [rem and em](https://zellwk.com/blog/rem-vs-em/) - how to use rem and em
* [CSS Diner](https://flukeout.github.io/) - practice selectors
* [Flexbox Froggy](http://flexboxfroggy.com/) - practice some flex display!

You'll eventually start using a pre-processer and start writting [sass], which is awesome. And you'll start using a framework like [Bootstrap] or [Foundation], both of which are probably way overkill for small, simple projects. Definitely try them because you'll want to be familiar with them, but then consider trying a more minimal framework like [skeleton] or [milligram].

[BEM]: https://css-tricks.com/bem-101/
[Suit]: https://github.com/suitcss/suit/blob/master/doc/naming-conventions.md
[sass]: http://sass-lang.com/
[Bootstrap]: http://getbootstrap.com/
[Foundation]: http://foundation.zurb.com/
[skeleton]: http://getskeleton.com/
[milligram]: https://milligram.github.io/

## JavaScript

* [exercism](http://exercism.io/) - complete coding challenges

* [eloquent javascript](http://eloquentjavascript.net/) - read it and complete the exercises

## Podcasts and Books and Blogs

Supplemental stuff, if your brain can handle it.

### Podcasts

I tried listening to podcasts a little bit, but never really got into it. Nonetheless, here are some that I remember enjoying, and some that a classmate of mine recommend, sorted alphabetically.

* [changelog](https://changelog.com/podcast)
* [codepen](https://blog.codepen.io/radio/)
* [design details](https://spec.fm/podcasts/design-details)
* [developer on fire](http://developeronfire.com/)
* [developer tea](https://spec.fm/podcasts/developer-tea)
* [five minutes of JS](https://fivejs.codeschool.com/)
* [frontend five](https://frontendfive.codeschool.com/) - just five minutes
* [full stack radio](http://www.fullstackradio.com/)
* [js jabber](https://devchat.tv/js-jabber)
* [programming throwdown](http://www.programmingthrowdown.com/)
* [shop talk](http://shoptalkshow.com/)
* [sprint ux](https://www.sprintuxpodcast.com/) - by local Denver Devs
* [this developer's life](http://thisdeveloperslife.com/)
* [thoughtbot](http://giantrobots.fm/)
* [tim ferriss](http://tim.blog/podcast/) - not dev related, but productivity and business and lifehacky stuff
* [unmistakable creative](https://unmistakablecreative.com/podcast/)

### Books

* The Pragmatic Programmer - It's on literally everybody's required reading list. I read it. It's good.

* Learn to Program

### Blogs

* Reddit. Maybe start with [/r/web_design](https://www.reddit.com/r/web_design/) and branch out to "related subreddits" in the side bar

* Medium. Follow a few tags like [design](https://medium.com/tag/design) and [web-development](https://medium.com/tag/web-development)

* [Hacker News](https://news.ycombinator.com/). Aggregator. Not a blog.
