# An About Me Page

Hello! I'll have you know that in the writing of this page, I considered a lot of things that I could potentially show off. 

In order:

- *I like markdown.* It's a nice way of notating things in a rational and easy on the eyes manner. It was a long journey from learning Google Docs to learning Word, and finally I ended up here. 
- *I like things to look visually cohesive and appealing.* 

> Once upon a time, I obtained a dark mode extension on Google Chrome, and then I spent the next three days (and additional hours besides), learning how to forever banish the evil white scrollbar from the sides of my newly darkened internet. That led me down a rabbit hole of command line flags; nowadays, my internet browsing is absent of those evil 20 px of space that most people have on their screens.

The first thing that I learned to do, which I would classify as software related, was **CSS**. 

I'm an avid reader, I will admit that readily. It matters to me (quite a bit) how things appear on the Internet—especially when I spend the majority of my time online devouring text. In the summer before attending UCSD, I found an extension called JustRead, which promised a user selectable reading mode—a feature that had existed for a long time on Safari, but never on Google Chrome. 

I tried it out. The features were interesting, but to be quite honest, the default styles were atrocious, and from hence on, I took it upon myself to traverse each part of that default CSS so that I could construct a more favorable stylesheet of my own. 

The fonts and the styling of headers were the easiest. After that, I looked at blockquotes, and color palettes. From there, I began an obsessive crusade to style scrollbars... which has only relaxed after I found out about command line flags in Chromium, and `--enable-features=OverlayScrollbar` in particular. 

## Rambly Bits

Here's an image of stuff that I was studying last quarter.

![](rsa.jpg)

Here's my favorite **AHK** script. I have it running almost all the time. 

```
#NoEnv  ; Recommended for performance and compatibility with future AutoHotkey releases.
; #Warn  ; Enable warnings to assist with detecting common errors.
SendMode Input  ; Recommended for new scripts due to its superior speed and reliability.
SetWorkingDir %A_ScriptDir%  ; Ensures a consistent starting directory.

; en dash
!-::
SendInput, {–}
return
; em dash
^+-::
SendInput, {—}
return
```

This is a link to my [codepen](https://codepen.io/Adventurous_Aspen/pen/GRZZxxP). 

## Thinking Forward

This is a list of things that I need to do this quarter. 

- [x] Take CSE 110. 
- [ ] Write two thousand words a day for [NaNoWriMo](https://nanowrimo.org/).
- [ ] Not procrastinate on writing. 
- [ ] Not procrastinate on homework assignments. 
- [ ] Realize that the "available by" and "due by" dates are completely separate, and that one comes after the other. 
- [ ] Profit???



```
#NoEnv  ; Recommended for performance and compatibility with future AutoHotkey releases.
; #Warn  ; Enable warnings to assist with detecting common errors.
SendMode Input  ; Recommended for new scripts due to its superior speed and reliability.
SetWorkingDir %A_ScriptDir%  ; Ensures a consistent starting directory.

; en dash
!-::
SendInput, {–}
return
; em dash
^+-::
SendInput, {—}
return
```