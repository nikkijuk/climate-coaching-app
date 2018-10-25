# climate-coaching-app

Climate coaching-app is an experiment to formulate idea of massive mobile personal coaching platform 

## Goal

Save the world.

But yes: it's good question. It's not clear to me why would anyone use app for climate-coaching and why? who would do content? who would consume it? privately? with community? sharing all? sharing nothing? sharing when finished? sharing thru process or learning? 

It is also not clear to me what would be core functionality where to start and how much additional functionality is needed. Chat? Q&A? Information from authorized sources, lookup services, product ratings, calculators, ..

It only makes sense to go forward if idea gets so clear that it's possible to implement very focused tool that would be useful and solve some problem.

## motivational poster

at firts it sucks! always! get over it..

https://www.youtube.com/watch?v=3plREv4LyWo

## coaching program structure: idea 1

I've thought that coaching aims to change something. And change always means reflection, learning and action.

Coaching programs needs to be formulated somehow. How about using markdown, so that each program has always one file as root (aka index.html) and if needed each module could been saved as single file in corresponding subdirectory.

1. Metadata
2. Introduction
3. Modules
  * Module 1
    * Introduction
    * Lecture 1
    * Test 1
    * Action 1
    * (and so on)
    * Summary
    * Further information
  * Module 2
    * Introduction
    * Test 1
    * Action 1
    * Lectue 1
    * (and so on)
    * Summary
    * Further information
4. Summary
5. Further information
6. Credits

Note that this silly idea has following rationale
- coaching program can be written with any tool, there isn't any special authoring tools
- coaching program can be saved to git repository and exported to devices as single jar containing whole repository content
- git would allow versioning, but also co-operation on authoring content

## coaching program structure: idea 1

same as above, but not one document, but lot of markdown documents in directory structure like

/index.md
/modules/1/1_1_introduction.md 
/modules/1/1_2_lecture1.md
..
/modules/2/2_1_introduction.md
..

in this kind of structure each document corresponds to view in app

## open questions

It's not clear to me if data collection, calculation and summarizing is part of program. It seems to me that it would make sense to collect data so that it could be stored locally during execution of modules and later used together with other information. How this is to be done in generic format is open. Json, jxpath and simple operations (+,-,*,/) could be sufficient for some tasks - but as Android and iOs both have powerful sql database this could also be option. Anyway: writing sql is not core competence of perspons who are able to formulate course content. Hiding data structures would need some kind of macro language.

## implementation of coaching apps

Look ma, I found new toy

https://flutter.io/

and it can do lot of things

https://pub.dartlang.org/packages/sqflite



## authoring

markdown syntax

https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet

parsing and showing markdown

https://pub.dartlang.org/packages/flutter_markdown

## next steps

I'll try to iterate and formulate this - let's see - I really don't know if this is good or useful idea

## inspirations

https://www.uprightproject.com/model/

http://fp2w.org/
