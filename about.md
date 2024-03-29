---
layout: page
title: About Santulator
short_title: About
permalink: /about/
weight : 2
description: About Santulator, acknowledgements and thanks
image: /assets/Santulator-About.png
---

Santulator helps you run your Secret Santa draw simply and flexibly.  See the [download] page for details on how to download and run the program.  You can follow Santulator on Twitter at [@{{site.twitter.username}}]({{site.twitter.link}}).

The system is Open Source Software, published under the [Apache Licence, Version 2.0].  You can find the source code on GitHub [here][GitHub].

[Adam Carroll] is the principal author of Santulator.

# Technical Articles

* [Open Source & Secret Santa with Santulator] - In this post on the King Tech Blog I give some of the details on how Santulator works behind the scenes including how JavaFX CSS is used to create the festive colour scheme in the user interface.
* [Installable Java Apps with jpackage] - Santulator has native installable bundles for Mac, Linux and Windows.  This article explains how this was achieved.

# Acknowledgements and Thanks

Santulator wouldn't be possible without the amazing work of others on some great Open Source software.  The following is a list of a few of those projects:

* [JavaFX] is used for the Santulator user interface.  Take a look at the article [How JavaFX was used to build a desktop application] to find out more about using JavaFX.
* As part of every build, the user interface is tested automatically using [TestFX].  Read the guide [User Interface Testing with TestFX] to learn how to do this in your project.
* Several of the user interface controls come from the [ControlsFX] library.
* The Santulator software uses [Gluon Ignite] and [Guice] for dependency injection.  The article [Dependency Injection in JavaFX] explains how this can be done.
* [OpenPDF] is used to generate the PDF files that show the participants who they will be buying presents for.
* The installable bundles for Mac, Linux and Windows are built using _jpackage_.  You can read all about this in the article [Installable Java Apps with jpackage].

[Adam Carroll]:https://github.com/AdamCarroll/
[download]:/download
[Apache Licence, Version 2.0]:http://www.apache.org/licenses/LICENSE-2.0
[GitHub]:https://github.com/Santulator/Santulator

[How JavaFX was used to build a desktop application]:https://medium.com/techking/how-javafx-was-used-to-build-a-desktop-application-7d4c680d8dc
[User Interface Testing with TestFX]:https://medium.com/@adam_carroll/user-interface-testing-with-testfx-5747ba02b0ec
[Dependency Injection in JavaFX]:https://vocabhunter.github.io/2016/11/13/JavaFX-Dependency-Injection.html
[Installable Java Apps with jpackage]:https://vocabhunter.github.io/2021/07/10/installable-java-apps-with-jpackage.html
[Open Source & Secret Santa with Santulator]:https://medium.com/techking/open-source-secret-santa-with-santulator-9101972359fc

[JavaFX]:https://openjfx.io/
[ControlsFX]:https://github.com/controlsfx/controlsfx
[Gluon Ignite]:http://gluonhq.com/labs/ignite/
[Guice]:https://github.com/google/guice
[TestFX]:https://github.com/TestFX/TestFX
[OpenPDF]:https://github.com/LibrePDF/OpenPDF
