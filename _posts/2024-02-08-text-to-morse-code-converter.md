---
layout: post
title:  "Text to Morse Code Converter"
date:   2024-02-08 15:56:02 -0500
categories: python
published: true
permalink: /:categories/:title.html
---

This project involves creating a text-to-Morse code converter, comparing the outputs using Selenium. The first output uses a dictionary derived from the Morse code alphabet while the other takes the keys from that dictionary to check for accuracy.

Morse code was developed in the early 1830s by Samuel Morse and his colleague Alfred Vail, but became widely used by telegraph operators in war-like settings. It found widespread use in World War I and World War II in military communication, allowing commanders to send orders and coordinate troops over long distances. It was also crucial for commercial purposes, such as sending urgent messages related to business, trade, and transportation until it was replaced by the telephone.

This form of communication uses a series of dots and dashes to represent letters and numbers, allowing messages to be transmitted over long distances via telegraph wires.

### Program Description

This program tests if two English Morse code messages match.

1. The first Morse code message is developed by using Selenium to get its alphabet entirely by scraping from [this website](https://morsedecoder.com/). Using an input message as its output, the Morse code is created using the nested list from the Selenium-derived alphabet.

2. The second Morse code message is developed by sending that message to the Text input field from the aforementioned website and returning the output Morse code.

<h2>Lessons Learned:</h2>

- What programming language did you use? **Python**
- Why did you do this project? **I wanted to exclusively use Selenium to ensure that its outputs are equal, whether by creating a dictionary from it or by comparing the output from that innput equals the website's output.**
- What do you think you did well? **Selenium automates tasks, which makes life easy. If I had to automate some other task using this package, it would be very easy now.**
- What's the most important lesson you learned? **Selenium is a useful package, certainly. However, its execution time is still not that quick, and that needs to be taken into account when creating a program relying on it.**
- If you did this project again, what would you do differently? **While I challenged myself to use Selenium to create the dictionary of the English alphabet, I could've just used used the alphabet and input the characters in the text field. Creating a dictionary of the characters was unnecessary and tedious.** 