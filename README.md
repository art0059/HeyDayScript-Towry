# HeyDayScript-Towry

This is the virtual version of Auburn's Hey Day (http://sga.auburn.edu/hey-day/). It is where all of the students say hey to one another and get to know each other. Fill out the name tag and get greeted just like you would on the concourse.

# How the script works:
1. The script will first ask you to type in your name, like you would write on a name tag.
2. Once filled out, the script replies like a student: "Hey $name! I hope you have an awesome Hey Day! It was great to meet you, War Eage!"

# The script
```bash
#!/bin/bash

# You're walking on the concourse to class, you meet Aubie the Tiger, and he hands you a name tag
echo "Fill out the name tag: Hello! My name is _________"
read name

# The student beside you sees your name tag and greets you
echo "Hey $name! I hope you have an awesome Hey Day! It was great to meet you, War Eage!"
