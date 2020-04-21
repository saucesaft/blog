---
title: "Rubiks 1"
date: 2020-04-05T15:50:05-05:00
draft: false

tags:
- english
- software

categories:
- developing

---

I had this idea, there's this simple universal [algorithm](http://www.rossnazirullah.com/students/images/Rubiks.pdf) which if followed will lead you to have a "solved cube". Which by solved i refer to it having each face with 9 same colors each. Now that's easy to process, but what if i wanted to have a custom pattern? What if my solved state wasn't the ordinary.

Let's say my solved state was the ordinary one but with the center pieces shifted to the right, on paper, if we ran the algorithms from the pdf but with the modifications we mentioned, we would end up with the rubik's cube with the pattern we wanted.

Now, to achieve this im programming a rubiks cube engine in c++ and openframeworks with this algorithm implemented. If you didn't understood my theory, wait until i release the software and try it for yourself :)
