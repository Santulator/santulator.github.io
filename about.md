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

* [Using the Java Packager with JDK 11] - Santulator has native installable bundles for Mac, Linux and Windows.  This article explains how this was achieved.
* [Open Source & Secret Santa with Santulator] - In this post on the King Tech Blog I give some of the details on how Santulator works behind the scenes including how JavaFX CSS is used to create the festive colour scheme in the user interface.

# Acknowledgements and Thanks

Santulator wouldn't be possible without the amazing work of others on some great Open Source software.  The following is a list of a few of those projects:

* [JavaFX] is used for the Santulator user interface.  Take a look at the article [How JavaFX was used to build a desktop application] to find out more about using JavaFX.
* As part of every build, the user interface is tested automatically using [TestFX].  Read the guide [User Interface Testing with TestFX] to learn how to do this in your project.
* Several of the user interface controls come from the [ControlsFX] library.
* The Santulator software uses [Gluon Ignite] and [Guice] for dependency injection.  The article [Dependency Injection in JavaFX] explains how this can be done.
* [OpenPDF] is used to generate the PDF files that show the participants who they will be buying presents for.
* The installable bundles for Mac, Linux and Windows are built using the Java Packager.  You can read all about this in the article [Using the Java Packager with JDK 11].

[Adam Carroll]:https://github.com/AdamCarroll/
[download]:/download
[Apache Licence, Version 2.0]:http://www.apache.org/licenses/LICENSE-2.0
[GitHub]:https://github.com/Santulator/Santulator

[How JavaFX was used to build a desktop application]:https://medium.com/techking/how-javafx-was-used-to-build-a-desktop-application-7d4c680d8dc
[User Interface Testing with TestFX]:https://medium.com/@adam_carroll/user-interface-testing-with-testfx-5747ba02b0ec
[Dependency Injection in JavaFX]:https://vocabhunter.github.io/2016/11/13/JavaFX-Dependency-Injection.html
[Using the Java Packager with JDK 11]:https://medium.com/@adam_carroll/java-packager-with-jdk11-31b3d620f4a8
[Open Source & Secret Santa with Santulator]:https://medium.com/techking/open-source-secret-santa-with-santulator-9101972359fc

[JavaFX]:https://openjfx.io/
[ControlsFX]:https://github.com/controlsfx/controlsfx
[Gluon Ignite]:http://gluonhq.com/labs/ignite/
[Guice]:https://github.com/google/guice
[TestFX]:https://github.com/TestFX/TestFX
[OpenPDF]:https://github.com/LibrePDF/OpenPDF
