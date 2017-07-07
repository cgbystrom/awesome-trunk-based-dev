# Awesome trunk based development [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
A curated list of everything related to trunk based development.


## What is trunk based development?

A short summary taken from [trunkbaseddevelopment.com](https://trunkbaseddevelopment.com) describes it as this:

> A source-control branching model, where developers collaborate on code in a single branch called ‘trunk’ *, resist any pressure to create other long-lived development branches by employing documented techniques, avoid merge hell, do not break the build, and live happily ever after.

For a more in-depth introduction to the idea, I highly recommend the linked site above by [Paul Hammant](https://paulhammant.com/).

Since I've been maintaining a list of sites, videos and blog posts on trunk based development, I figured it could be of more use if I made it public instead. It's simply a collection of links on this topic :smile: If you'd like to contribute, do send a pull request!

## Trunk based development

 * [Trunk-Based Development](https://trunkbaseddevelopment.com/) [website, 2017]
 * [Trunk-Based Development Economics](https://www.youtube.com/watch?v=meB_SWzZm8M) [video, 2017]
 * [How Google Builds Web Frameworks](https://medium.freecodecamp.org/how-google-builds-a-web-framework-5eeddd691dea) [blog post, 2017]
 * [How Chromium Works](https://medium.com/@aboodman/in-march-2011-i-drafted-an-article-explaining-how-the-team-responsible-for-google-chrome-ships-c479ba623a1b) [blog post, 2015]

## Monorepo

 * [Why Google Stores Billions of Lines of Code in a Single Repository](https://cacm.acm.org/magazines/2016/7/204032-why-google-stores-billions-of-lines-of-code-in-a-single-repository/fulltext) [article, 2016]
 * [Why Google Stores Billions of Lines of Code in a Single Repository](https://www.youtube.com/watch?v=W71BTkUbdqE) [video, 2015]

## Version Control

 * [The largest Git repo on the planet](https://blogs.msdn.microsoft.com/bharry/2017/05/24/the-largest-git-repo-on-the-planet/) [blog post, 2017]<br> Microsoft explaining how they moved the Windows code base to Git.
 * [Scaling Mercurial at Facebook](https://code.facebook.com/posts/218678814984400/scaling-mercurial-at-facebook/) [blog post, 2014]
 * [Scaling Mercurial at Facebook: Insights from the Other Side](https://www.youtube.com/watch?v=gOVD-DrUpwQ) [video, 2017]
 * [Scaling Source Control at Facebook](https://www.youtube.com/watch?v=Dlguc63cRXg) [video, 2014]
 * [Still All on One Server: Perforce at Scale](https://static.googleusercontent.com/media/research.google.com/en//pubs/archive/39983.pdf) [paper pdf, 2011]
 * [Still All on One Server: Perforce at Scale](http://info.perforce.com/rs/perforce/images/stillallononeserver.pdf) [slides pdf, 2011]
 * [Git Virtual File System](https://atscaleconference.com/videos/git-virtual-file-system/) [video, 2017]
 * [Scaling Git at Microsoft](https://www.youtube.com/watch?v=g_MPGU_m01s) [video, 2017]
 * [Scaling Git at Twitter](https://www.youtube.com/watch?v=bjh4DHuOf4E) [video, 2015]
 * [Git at Google: Making Big Projects (and Everyone Else) Happy](https://www.youtube.com/watch?v=cY34mr71ky8) [video, 2015]

## Builds and Continuous Integration

 * [Bazel](https://bazel.build/) [website, 2017] by Google
 * [Buck](https://buckbuild.com/) [website, 2017] by Facebook
 * [Pants](http://www.pantsbuild.org/) [website, 2017] by Twitter
 * [Crazy Fun Build](https://github.com/SeleniumHQ/selenium/wiki/Crazy-Fun-Build) [docs, 2015]. Used by Selenium, being phased out for Buck.
 * [Build in the Cloud: Distributing Build Outputs (at Google)](http://google-engtools.blogspot.se/2011/10/build-in-cloud-distributing-build.html) [blog post, 2011]
 * [Build in the Cloud: Distributing Build Steps (at Google)](http://google-engtools.blogspot.se/2011/09/build-in-cloud-distributing-build-steps.html) [blog post, 2011]
 * [Build in the Cloud: How the Build System works (at Google)](http://google-engtools.blogspot.se/2011/08/build-in-cloud-how-build-system-works.html) [blog post, 2011]
 * [Tools for Continuous Integration at Google Scale](https://www.youtube.com/watch?v=KH2_sB1A6lA) [video, 2012]
 * [Building Software at Google Scale Tech Talk](https://www.youtube.com/watch?v=2qv3fcXW1mg) [video, 2012]
 * [Building Software at Google Scale: Bazel](https://www.youtube.com/watch?v=6GCDfoAOKIY) [video, 2016]
 * [Bazel: Google’s extensible, multilingual, scalable build system](https://atscaleconference.com/videos/bazel-googles-extensible-multilingual-scalable-build-system/) [video, 2017]
 * [Building a Distributed Build System at Google Scale](https://www.youtube.com/watch?v=y0IutoPKTNE) [video, 2016]


## Contributing

Pull requests are more than welcome. The common theme above are challenges that arise when scaling the number of developers while keeping a central infrastructure (be it VCS, build systems, CI servers and so on).

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Carl Byström](http://cgbystrom.com) has waived all copyright and related or neighboring rights to this work.
