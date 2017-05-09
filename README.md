# susi_skill_data
This is the storage place for susi skills. It is for now a temporary solution for a wiki-like skill editing service that we want to create in the near future.

## Installation
This repository must be cloned along https://github.com/fossasia/susi_server to make it available to susi.
The production plattform of http://susi.ai will do a `git pull origin master` every minute. That means, every change will be available very soon.

## Create a new skill
Creation of a new skill is easy, DO NOT PANIC!

### Learn the skill language
Read https://github.com/fossasia/susi_skill_data/blob/master/README_susi_skill_language_tutorial.md and test your skill using a susi dream! Then, if your susi dream works, add the skill to this repository, read next topic...

### Add the skill to the skill sets
To add a new skill choose of of the topics

* assistants
* entertainment
* knowledge
* problemsolving
* shopping
* smalltalk

and add your new skill into a subdirectory of https://github.com/fossasia/susi_skill_data/tree/master/models/general

Your skill must be placed in a language-dependent subdirectory. There, files containing sets of skills are called 'expert'.
Place your skill along one existing expert, or create a new one.
Do NOT create a new model in the models subfolder and do NOT create a new topic in the models/general subfolder.
If you want a new topic, create an issue and describe your topic and it's purpose.

## License
All new skills shall be licensed under CC0 https://creativecommons.org/publicdomain/zero/1.0/deed.de 
We choosed this data because many skills may be similar to knowledge as published by wikidata.org which licenses it's data under CC0 as well.
If you take skill data from non-cc0 sources, you may do so but please also copy the license information.
