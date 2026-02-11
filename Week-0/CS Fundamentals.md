## Table of Contents
* [[#1. Welcome & Introduction of AI|Welcome & Introduction of AI]]
	* [[#Welcome to CS50x 2026]]
	* [[#Introduction to AI]]
* [[#2. VSCode & Code Efficiency|VSCode & Code Efficiency]] 
* [[#3. Computer Science & Problem Solving|Computer Science & Problem Solving]]
	* [#What Is Computer Science]
	* [#How Computers Interpret The World]
		* [#Unary]
		* [#Binary]
* [[#4. Data Representation (ASCII,Unicode,RGB)|Data Representation (ASCII,Unicode,RGB)]]
	* [#ASCII]
	* [#Unicode]
	* [#RGB, Videos & Music]
* [[#5. Algorithms & Pseudocode|Algorithms & Pseudocode]]
* [[#6. What's Ahead|What's Ahead]] 
* **Implementation:** [[00_scratch_logic|Go to Scratch Logic Notes →]]
---
## 1. Welcome & Introduction of AI
### Welcome to CS50x 2026
Harvard's University CS50x is a course introduction to the **computer science** and the art of **programming**, it is for everybody with or without programming experience.
This course teaches you on how to solve problems, both with or without code, with an emphasis on accuracy, design and style. It includes topics such as **computational thinking**, **abstraction**, **algorithms** & **data structures**. More than teaching you how to program in one language it ultimately teaches you on how to program fundamentally and how to teach oneself to new languages, making you think on how computers work, thinking logically and efficiently. 
The course starts with language called ***C***, then transitions to ***Python***, ***SQL***, even concepts such as ***AI****(Artificial Intelligence)* and ***Machine Learning***, all the way to **Flask*** and finishing with ***CSS***, ***HTML*** & ***JavaScript*** to create web & mobile apps. Culminating in a final project of your own and upon finishing all your tasks you receive a world-class renown certificate from Harvard University, helping you getting higher chances to get a job in the field of tech.
### Introduction to AI
***AI*** or so called **Artificial Intelligence** as we all know it has become extremely advanced and a exciting topic not only in computer science but in the world!
Some worry and others take advantage of this technology, it not only can improve our lives and augment productivity, in some cases it lead to several layoffs due to companies investing and betting on this advancements such as the example we saw last year in 2025 (*if you're reading this in 2026*). Thus for it is important to understand not only rely but be the pilot of this new technology, by learning the fundamentals under AI's hood, thus empowering it and open a new horizon of knowledge, opportunities for not only you but to those you serve and the world!
Instead of getting intimidated you will feel assured that you'll not only be an asset but a contributor.
In this course we will touch the surface and ins of ***Machine Learning*** and ***AI***, furthermore after being successful I will dive deep into this field by starting another of Harvard's University courses called [CS50's Introduction to Artificial Intelligence with Python](!https://harvardonline.harvard.edu/course/cs50s-introduction-artificial-intelligence-python) 

---
## 2. VSCode & Code Efficiency
Before beginning to learn how to code or getting my hands dirty with any programming language it is important to know where we will be spend most of our time and do all the working later on, in this course and in my career.
A text editor is a program where you type characters itself it doesn't understand what you write it self but if you add to it a compiler (*that is a separate program and we will be using it to write code in C*) it translates the source code you wrote into zeros (**0**) and ones (**1**), when you mix these two together you get an **IDE**(*Integrated Development Environment*) which is the complete toolbox, that include not only the previous tools but a debugging tool all in one window.

It is important to understand that writing code takes space in your computers memory and if it passes that space the program might not run the way you intend to. This is important later on because it will teach you to write code efficiently in a way that saves not only space, time but it is more understandable to the computer in some cases it can be reused and easily maintained.

---
## 3. Computer Science & Problem Solving
### What Is Computer Science?
**Computer Science** or **Computational Thinking** is a form of taking some input and creating some output, thus solving a problem. What happens in between the input and the output, we can call it a black-box or our canvas and its where all the magic happens and what this course will focus on.
![[Pasted image 20260210230537.png|center|center]]
### How Computers Interpret the World
Us humans perceive the world through objects, definitions, and sensory experiences—both visual and non-visual. Computers, however they do not possess the same, sensory abilities and do not "see", they store and interpret data through billions of tiny switches called transistors that are either **on** or **off**. By using globally defined systems, these 'on/off' states symbolize complex information. Before exploring how these modern definitions were established, it is essential to understand the **counting system**.

A **counting system** or **number system** is a set of rules for using symbols to represent "how many" of something exists, so its a way to quantify the using numeric values. Every system relies on a **base** that quantifies or determines of many values are inside for example "tenths", "hundreds", "thousands". This helps us create a framework to map the physical world into a structured mathematical format. 
There are two types of **number system** and translate data:
	* Unary
	* Binary
#### Unary
**Unary System** is the simplest way to count that we humans tend to use when counting with fingers or the average person thinks, it is also called as **base-1**.
For example: 
*"There is a number of people that are coming to have lunch at your house and suddenly someone brings a number of people that you were not expecting, so the obvious thing is to count them on by one"
You look to each of them and start pointing or using your fingers(subconsciously count yourself without pointing):

| **Person** | **Number** |
| ---------- | ---------- |
| Alissa     | 1          |
| Jhon       | 2          |
| Dwayne     | 3          |
| Carlos     | 4          |
| Maria      | 5          |
| Yasmina    | 6          |
| Yourself   | 7          |
| Daniela    | 8          |
Know knowing the total you can set the plates.
*
This is a clear example of unary system.
 > <center><strong>Unary = 1 Digit = Base 1</strong></center>
#### Binary System
The **Binary System** is a base-2 numbering system that serves as the fundamental language of all modern computing. Unlike the decimal system (base-10) used by humans, which relies on ten digits (0–9), binary uses only two unique symbols: **0 and 1**. This simplicity is by design, as it maps directly to the physical reality of computer hardware, where millions of microscopic switches (transistors) can only exist in one of two states—either **off** (represented by 0) or **on** (represented by 1).

By grouping these individual bits (binary digits) together, computers can represent complex information far beyond simple numbers. Through the logic of positional notation—where the value of each bit doubles as you move from right to left (1,2,4,8,16...)—a sequence of **zeros** (0) and **ones** (1) can be used to encode anything from a single letter in an email to a pixel in a high-definition video. Essentially, binary acts as the bridge that allows physical electricity to be interpreted as digital data.
> <center><strong>Unary = 2 Digit = Base 2</strong></center>

Early computers often used 8-bit systems, meaning they could process **8-bits** of data at a time. With **8-bits**, you can represent 256 different values (from 0 to 255). These values can be used to represent characters, numbers, or other data. For example, the ASCII standard assigns specific numbers to characters, allowing computers to interpret and display text.

| 128   | 64    | 32    | 16    | 8     | 4     | 2     | 1     |
| ----- | ----- | ----- | ----- | ----- | ----- | ----- | ----- |
| $2^7$ | $2^6$ | $2^5$ | $2^4$ | $2^3$ | $2^2$ | $2^1$ | $2^0$ |
| 0     | 0     | 0     | 0     | 0     | 0     | 0     | 0     |
With time gradually and with technological advancements computers could process **16-bits**, **32-bits** to **64-bits** (*some process can even go from 128-bits, 256-bits and 528-bits*
How would we be going by representing the number  **5**:
If the first bit of the 8-bits system is equal to **0** or **1** and the second bit is equal to **2** and the third bit is equal to **4** we can assume the following:
**00000101** = **5**
This is how computers interpret numbers in the next chapter we'll go more in depth on data representation. 
## 4. Data Representation (ASCII,Unicode,RGB)
As mentioned before computers use the binary system to interpret the world around us using a binary system with a certain amount of bits and assign those values to characters.
### ASCII
Just as numbers are binary patterns of **ones** (1) and **zeros** (0), letters are represented using them too. Since there is an overlap between the ones and zeros that represent numbers and letters, the **ASCII** (*American Standard Code for Information Interchange*) standard was created to map specific letters to specific numbers.
Here is the map of **ASCII** values:
![[Pasted image 20260211230757.png|center|800]]

### UNICODE
While ASCII was the first major standard, it was limited to only 128 characters—enough for the English alphabet but insufficient for a globalized world. **Unicode** was created to solve this by providing a unique "code point" for every character in every language on Earth. Unlike older systems, Unicode is expansive enough to cover thousands of symbols, ranging from ancient hieroglyphs and complex mathematical notations to the diverse scripts of Africa, Asia, and the Middle East.

In today's digital landscape, Unicode is the universal standard that ensures a message sent from Mozambique can be read perfectly in Japan or Brazil without the text becoming garbled. Beyond just text, its most visible use in modern culture is the **emoji**; every time you use a 🇲🇿 flag or a ❤️ in a chat, you are sending a specific Unicode number that every modern device recognizes. By creating a unified digital language, Unicode has become the invisible backbone of global communication, web development, and social media.

> <center><strong>ASCII</strong>(128 characters) → <strong>Unicode</strong> (150,000+ characters)</center>

### RGB Videos & Music
**RGB (Red, Green, Blue)** is a system that represents colors by mixing three primary light sources in varying intensities. In a digital context, each color is typically assigned a value from 0 to 255. This range is not accidental; 255 is the maximum value that can be stored in **8 bits (1 byte)**. Just as **ASCII** uses a byte to represent a specific character like "A," an RGB system uses three bytes—one for each color channel—to represent a single specific color.

The relationship between **RGB**, **ASCII**, and **Unicode** is found in the concept of **abstraction**. All three systems take an abstract human idea (a color, a letter, or an emoji) and map it to a specific numeric code. While **ASCII** and **Unicode** allow a computer to "read" by mapping numbers to glyph, **RGB** allows a computer to "see" by mapping numbers to the intensity of light on a screen. Both systems rely on the same underlying binary infrastructure to turn raw electricity into human-meaningful information.

An **Image** is simply a grid of pixels where each pixel is assigned an RGB value. When thousands of these colored dots are packed together, our eyes perceive a continuous picture. 

**Videos** take this a step further by utilizing the concept of "frames per second"; a video is essentially a rapid sequence of images shown one after another, creating the illusion of motion.

**Music** is represented by sampling sound waves and converting their frequency and amplitude into numbers. Because a computer cannot store a continuous wave, it takes thousands of "snapshots" of the sound every second (sampling) and stores each snapshot as a binary value. When played back, the computer translates these numbers back into electrical signals that vibrate your speakers, recreating the original sound.

