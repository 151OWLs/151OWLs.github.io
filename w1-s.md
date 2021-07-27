---
layout: default
title: Week 1 Solutions
permalink: /w1-s/
---

[Back](session-notes.markdown)

# What was covered: 
### Classes, types, access attributes, main method

#### Warm up:
**How would you describe the role of a constructor to someone who does not have knowledge of CS?**

<ul>
<li>Compare methods to a recipe and constructor is like creating a cupcake
    <ul><li>Classes = blueprints & objects = final product</li>
    <li>constructor is process of creating this final product</li></ul>
    </li>
</ul>

#### Access Attributes:
**Why do we care about these access attributes? In what scenario would we want something to be public? Private?**
<ul>
    <li>Helps to determine safety protocol of files and code</li>
    <li>Important to keep variables within classes hidden from rest of program, why?
    <ul>
        <li> Allows for us to have more control over the variables, can create setter and getters!
        <ul>
            <li>Setters and getters?</li>
            <li>Setter = method to set value of a variable</li>
            <li> Getter = method within the class to return the value of a variable
            <ul>
                <li>Why have a “getter”?</li>
                <li>More control, ie want to have some arithmetic with the getter, can just put it once in there </li>
            </ul></li>
        </ul></li>
    </ul></li>
</ul>

**Oftentimes, people confuse the difference between protected and private. Come up with a (jingle, saying, picture, acrostic, etc) to help you and your peers remember the role of public, private, and protected.**
<ul>
    <li>Private rhymes with inside it! (where you have to be when you access them)</li>
</ul>

#### Main Method:
**What makes the main method special?**
<ul>
    <li>Where the program would start the execution of the code! (driver)</li>
    <li>Function that the Java Virtual Machine runs</li>
<ul>

**What would happen if you switched public to private?**
<ul>
    <li>It wouldn't run, because it cannot be accessed</li>
</ul>