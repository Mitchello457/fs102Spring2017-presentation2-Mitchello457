# fs102Spring2017-presentation2-Mitchello457

This repository contains the HTML source code and additional resources for a presentation that I, [Mitchell Lachat](https://mitchello457.github.io/), gave in my FS 102 Software Everywhere class at [Allegheny College](http://allegheny.edu/). It is based off of a presentation that my professor, [Gregory Kapfhammer](http://www.cs.allegheny.edu/sites/gkapfham/), gave during a panel at the 27th International Conference on Software Engineering and Knowledge Engineering (SEKE 2015). The presentation's source code uses the reveal.js framework to control the display of each slide. The original presentation can be found [here](https://github.com/gkapfham/seke2015-panel-presentation).

Are you interested in previewing the presentation without having to download the code and resources from the GitHub
site? Well, you can! Please view [The Dulling of Skillsets](https://rawgit.com/Mitchello457/fs102Spring2017-presentation2-Mitchello457/master/The_Dulling_of_Skillsets.html).

## Installation Instructions

You can type the following command if you want to clone this repository:

```shell
git clone https://github.com/gkapfham/seke2015-panel-presentation.git
```

Please note that the presentation uses local fonts so that it can be displayed at a conference on a laptop that either
may not have access to the Internet or may only have unreliable Internet access. Some browsers may disallow the loading
of local fonts due to security reasons. However, it should be possible for you to view the presentation correctly when
using Chrome or Chromium on the Ubuntu operating system &mdash; this is my primary development environment and the one
that I used to give the presentation. However, I anticipate that the presentation slides should display correctly on a
wide variety of operating systems and browsers.

I have found that some versions of Chrome and Chromium do not quickly load the full-screen images that I use as
backgrounds. If you notice this problem as well, then I would encourage you to "serve" the presentation with a local Web
server, such as the Ruby-based one available at [jlong/serve](https://github.com/jlong/serve). If you adopt this
approach, then you should type the following command:

```shell
serve 4100
```

Now, you can navigate to the Web site `http://localhost:4100/seke2015_panel.html` and view the presentation.  Ultimately,
if you are unable to get the presentation to display correctly in your own web browser, then please open a new issue and
I will attempt to resolve your concerns.
