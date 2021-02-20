# Hello! 

This is the repo for an example data analysis using the Open Source [Steinmetz Neuropixel Dataset](http://data.cortexlab.net/). The aim of this project is to roadtest different skill sets in an "open science" environment and be able to collaborate more freely. 

:brain: Dense arrays (the physical type) were used to record from mice during a go/no-go task. It's an incredibly rich dataset for understanding movement, decisions, visual processing (and lots more I haven't thought of). 

The easiest way to see what's in the data is to load it up and to read through the key labels on the dataset:

```
# choose one recording session (eg.20) to get labels
session_20 = steinmetz_data[20]
keys = session_20.keys()
print(keys)

```
as a note, session 4 has really good Primary Visual Cortex data so that's always a good place to start. 

You can read more about the neuropixel dataset [here](https://www.biorxiv.org/content/10.1101/2020.10.27.358291v1) 


## Goals

The project has 4 current objectives:
1. Use a [Binder](https://mybinder.org/) environment to write code openly and support reproducibility
2. Explore the absolutely awesome dataset from Steinmetz's team and learn more about neural processing
3. Continue learning and iterating over the code so that what took 20 lines, will eventually be done in 4
4. Create reuseable code (eg. using functions)


## Status

Currently hosted on Binder
:bug: Key bugs are on logistic-regression branch



## Built With

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/BrainonSilicon/NeuropixelAnalyses/HEAD)


## Get Started

There's a few entry points :star2:
- you can click the git sheild above which will take you to Binder (or follow the link [here](https://mybinder.org/v2/gh/BrainonSilicon/NeuropixelAnalyses/HEAD))
- You can open an issue or comment on a currently open issue to fix some bug 
- Or just reach out! 



## Tests

Inline-style: 
![Good Code](https://imgs.xkcd.com/comics/good_code.png "Good Code from xkcd")

This project is striving to implement [TDD](http://agiledata.org/essays/tdd.html#:~:text=Test%2Ddriven%20development%20(TDD)%20is%20a%20development%20technique%20where,Agile%20DBAs%20for%20database%20development.) and learning to write more informative Error messages is in the roadmap. If you would like to suggest or contribute to this process, feel free to open an Issue or make a PR. 

## Credits

This is all made possible because of the [Nick Steinmetz](http://www.nicksteinmetz.com/) and the Neuropixel researchers who have made this data available for use.


## License

[![Open Source](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)](https://opensource.org/)
[![MIT License](https://img.shields.io/apm/l/atomic-design-ui.svg?)](https://github.com/tterb/atomic-design-ui/blob/master/LICENSEs)
