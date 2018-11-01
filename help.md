---
layout: page
title: How to Use Santulator
short_title: Help
permalink: /help/
weight : 3
description: How to use Santulator
image: /assets/Santulator-Help.png
---

## Introduction

Welcome to Santulator, the simple, flexible and fun way to run Secret Santa draws for your family and friends.  And it's completely free with no advertising and no need to load your private family details to some random place on the internet.  You run Santulator on your own computer to get a collection of beautiful PDF files, rather like little Christmas cards, to send out to the people who will participate in the draw.  Just for fun, you can choose to add a password to the files to keep the secrets of the draw.

If you want to make sure Uncle John doesn't get Auntie Joan in the draw as, being married, they ought to be buying one another presents anyway then, no problem.  You can add any restrictions you like to the draw.  If you are running a special draw for your nieces and nephews where the adults buy the presents and the children receive the gifts then you can do that too by marking the role of each participant.

## Contents

* Do not remove this line (it will not be displayed)
{:toc}

## Downloading and Installing Santulator

In no time at all you can download and install Santulator.  All the information you need is on the [download](/download) page.

## Your First Secret Santa Draw

Let's run through a simple secret Santa draw.  Albert, Beryl, Carla and David work together.  To begin we add each name to the first column of the draw table.  A row in the table represents a participant in the draw.  You can see the little person icon next to each person's name.  Once you've added someone's name, click the plus icon or just press return on a name to move on to the next person.

![Santulator add participants](/assets/Santulator-Add-Participants-1.gif){: .center-image }

Now we give the draw a title and just for fun we'll add the top-secret password "surprise”.

![Santulator draw title](/assets/Santulator-Draw-Title-1.gif){: .center-image }

Let's get Santulator to do it's magic.  Press the "Run the Draw” button.  This opens up a simple 3-stage wizard.
![Santulator draw title](/assets/Santulator-Draw-Wizard-1.gif){: .center-image }
Pressing "Start the Draw” will shuffle the participants and make sure that everyone has someone different to buy a present for.  The "Next” button takes you to the second stage of the wizard.  Here you can press "Save Draw Results” to choose the directory on your computer where you would like to store the PDF files.  When this is done, press "Next” to move on to the third and final stage of the wizard.  All that remains is to collect the results of the draw.  When you press "Open Draw Results” you will see the folder with a set of files, one for each participant in the draw.

## Adding Exclusions

Sometimes you need to make sure that certain people are excluded from giving presents to certain other people.  The most common reason to do this is for a family Secret Santa draw.  Auntie Joan and Uncle John are married and will be buying one another presents anyway so you need to make sure they don't get each other in the draw.  To do this, go to the row for Joan and add John as a name in the list of exclusions on the right hand side.  Do the same for John, adding Joan's name to the exclusions for her.

![Santulator exclusions](/assets/Santulator-Exclusions-1.gif){: .center-image }

## A More Complex Draw

Perhaps in your family the lucky nieces and nephews receive presents and it is the job of the aunts and uncles to buy them those presents.  You can set up a special type of Secret Santa draw in Santulator for this.  Each person in a Santulator draw has one of three roles: they are either a present giver, a present receiver or both.  By default every participant is both a present giver and a present receiver.  However for our special draw we'll assign some special roles.  First of all let's add just the nieces and nephews and mark them as present receivers only so that they don't have to buy any presents:

![Santulator present receivers](/assets/Santulator-Present-Receivers-1.gif){: .center-image }

Next we need to add the generous aunts and uncles, this time marking their role as present givers.  They won't be receiving any presents:

![Santulator present givers](/assets/Santulator-Present-Givers-1.gif){: .center-image }

Once this is done we can decide if we want to set the draw name and add a secret password and then finally run the draw.  Just as before we run through the draw wizard and create a set of beautiful PDF files to send out to the people marked as present givers, in this case, just the aunts and uncles.

## Saving and Loading Your Session

If you need to run the same draw with the same people each year, you might like to save your session to avoid typing all the names in next time round.  If you press the "Save” button (or alternatively use one of the corresponding menu items) you can store the details of the draw setup in a `.santa` file.  These `.santa` files contain everything from the draw table (the names of participants, their roles and any exclusions) along with the name of the draw and the secret password, if you have set one.  Having saved the session you can reopen it at any time using the "Open" button or the corresponding menu item.  Note that `.santa` files just contain the draw setup but not the actual draw results.  The draw results are created each time you press "Run the Draw” to open the draw wizard and are saved as PDF files.

## News and Announcements

If you'd like to stay up-to-date on the latest on Santulator, follow [@{{site.twitter.username}}]({{site.twitter.link}}) on Twitter.  And for the programmers out there, don't forget you can always fork the [Santulator Open Source project on GitHub](https://github.com/Santulator/Santulator).

## What to Do if You Find a Bug

If you find a bug, please report it.  You can find details on how to do this on the [How to Report a Bug](/issues) page.

If you can fix the problem yourself, please send a [GitHub Pull Request](https://help.github.com/articles/about-pull-requests/).