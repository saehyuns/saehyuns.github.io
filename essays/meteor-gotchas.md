---
layout: essay
type: essay
title: "One Meteoric Problems!"
date: 2017-10-19
labels:
  - Software Engineering
  - Meteor
---

As opposed to everyone else, I did not have any major issues while using the Meteor application. However, one problem that I did have for while doing my digits practice WOD was that when I published/subscribed to the 'Contacts' database in part 4, the database did not appear on the home page. First, as explained in the screencast, I checked to see if everything was imported, it turned out that everything was imported in the index.js and main.js files. Then, I watched the video again to make sure that everything I did matched up with what was done in the video. I found that everything did match up and was basically like how he wanted the code to look like. I went back to my localhost:3000 and kept refreshing the page continously. All that effort with no results to reflect it. I then decided to restart my IntelliJ application and refreshed the home page once more. There was no change. I decided to take a break from the practice WOD to get my mind off of it and to de-stress. I went to go workout, eat, play some tennis, work on my other assignments for other classes, etc. Later that day, I decided to go back to the WOD and read through it again. The first thing I saw when reading the description was:

```
Note that switching GitHub branches on a running meteor application has t
he potential to put the application into an inconsistent state. To minimi
ze problems, whenever you switch branches while doing meteor development, 
it is best to:

1. Quit meteor.
2. Invoke meteor reset to clear out the contents of the database.
3. Re-invoke meteor. For applications based upon meteor-application-template, you can use meteor npm run start, which runs a    script found in package.json that resolves to meteor --no-release-check --settings ../config/settings.development.json.
```

I then immediately went to the terminal and typed:

```
^C
meteor reset
meteor npm run start
```

Those three lines of commands, which took less than 10 seconds to type was all I needed to get the database that I published/subscribed to show up. A problem that took me hours to try and figure out was right there all along. From then on, the first thing that I would do after switching branches is to reset and restart the meteor server to make sure that it puts the application back to a consistent state. My lesson was learned. 
