# Meme Share App

##

![Alt Text](https://media.giphy.com/media/izymhRWpKR3XjLCbYd/giphy.gif)

# Introduction:-

In this codebase, I build an Android App that Randomly Generate a MEME using Reddit-API.

# Pre-requisites:-

You need to know:
- How to create ImageView, Button in an App.
- How to use LinearLayout and Constraint Layout Editor.
- What is Volley Library and How does it work.
- How to use Intent and its Attributes.
- How to use Singleton Class.
- How to call API from a website.


# Tools & Language:-

Android Studio

Kotlin and Android xml

##

# Project Description :- 

In this codebase, I was create a Meme Share Android App where users can click **Next** button to see the next MEME and click **Share** button to share the meme with their Friends.

In Android_main.xml, I use Constraint Layout, It resize the Image at its right position.
I create 2 Buttons **SHARE** and **NEXT**.

Load Random Image in our App, I use **VOLLEY LIBRARY**. Volley library calling the API.

[Volley is an HTTP library that makes networking for Android apps easier and most importantly, faster. Volley is available on GitHub.]

After that I extract The JSON file. 

This all things are done in **loadImage()** function

When User clicked the next Button **loadImage()** function again called and show Image.

User can Only share the extracted link/string when clicked on the share button.

Share button use **Intent** library which allow the user share the link in different apps which support text or link.

##



