---
layout: post
title:  "Stock Trading Project"
date:   2024-02-30 23:01:02 -0500
categories: python
published: true
permalink: /:categories/:title.html
---

This [program](https://github.com/add0794/stock-trading) not only tracks changes in its stock value, but automatically texts you when a significant event happens (e.g. 5% increase or decrease).

Make your investing life easier, and perhaps, stop using a certified financial analyst (CFA) to do the dirty work.

- What programming language did you use? **Python**
- Why did you do this project? **I wanted to create a program that makes it easy to track stock values and their changes. We rely heavily on manually checking them, but why not let Python do the heavy lifting?**
- What do you think you did well? **I emphasized modular programming by creating data_creation.py to create (or update) the JSON files.**
- What's the most important lesson you learned? **There's a package you must use to access the file holding environmental variables before they can be accessed.**
- If you did this project again, what would you do differently? **I would've put data_creation.py and create_json.py in the same module. Creating separate modules slows down the program and stores more memory.** 