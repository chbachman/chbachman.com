+++
title = "Work"
menu = "main"
+++

# Apple

## [Fitness+](https://www.apple.com/apple-fitness-plus/)

### iOS 14.3 - Fitness+ Initial Launch

[Apple Page](https://www.apple.com/newsroom/2020/12/apple-fitness-plus-the-future-of-fitness-launches-december-14/)

As one of the first engineers that worked on Fitness+, I helped build the iCloud server and CoreData infrastructure that powers iCloud Syncing and the Burn Bar.

### iOS 15 - Fitness+ Resume Workout

After launch, one of the biggest requests was the ability to resume a workout. This was a challenging feature to ship since we had less development time than usual. As well, we had made assumptions in our existing code that the video timestamp and the workout duration would always match. This meant that I had to edit large swaths of the codebase that I wasn't familiar with without causing regressions.

### iOS 16 - Fitness+ on iPhone

Fitness+ was designed to work with the Apple Watch. However, that limited our potential user base to only those who owned an Apple Watch. This year I was tasked with removing that requirement, expanding the potential userbase to billions of iPhone users. Similar to last year this involved breaking longstanding assumptions in our codebase but on a much larger scale.

This feature got dedicated time during the [September Keynote that year](https://youtu.be/ux6zXguiqxM?t=3982), as well as [placement on Apple's homepage](https://web.archive.org/web/20230103012713/https://www.apple.com/).

### iOS 17 - Fitness+ Custom Plans

During my last year at Fitness+, I got to lead the biggest feature we had since launch, Custom Plans. I was responsible for working with other engineers as well as Design and AI experts, keeping everyone on the same page and working to make sure we shipped with a successful feature. On the technical side it was the most involved feature we had shipped yet, taking lots of iteration to end up in a solid place. We had to build most things from scratch.

## Photos

I transferred to work on the watchOS Photos App, and helped to build the new watchOS 11 Photos Face. This was a new codebase, with a new group of people and a very ambitious feature. I designed the entire Phone <-> Watch communication stack and dealing with the logistics of selecting, processing, and syncing photos. This was a year extremely focused on performance, as we had very tight limits in what we could do, including a strict 5MB memory limit and limitations on when and where we could do work.

# Internship

### BMW

I was an intern at BMW for 2 summers during college, during which I helped build UI Testing frameworks for other BMW Engineers for their iOS App. The second summer I did development on the actual iOS App.
