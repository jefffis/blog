---
layout: post
title: 'Give a shit: How to not lose focus.'
context: 'Second in a series of two&ndash; to four&ndash;posts, the entirety is not determined yet&hellip;'
---

The title kinda says it all: Don't lose focus. Either of what you want your users to do on your site, but more specifically, don't lose the oft forgotten pseudo styling for interactions. CSS resets are great, but often times you'll reset default browser styling that, unless properly redefined, is critical to helping your users when interacting with any type of website.

Even in 2015, these necessary actions are understyled, or not styled at all. Please, stop screwing up your users experiences.

## :hover

This is the least often of the offenders, but it is something that is definitely taken for granted. Most times sites will apply styling to hover interactions with buttons, which is important for sure. But, where a lot of sites go wrong is by not properly setting user expectations with these styling choices. Most times I see a <code>:hover</code> style that is more appropropriate for an <code>:active</code> styling. For example, the hover changes the background color, border postioning, or even adds a faux-click styling to it. But to the user, this can be an odd inference, as they really haven't done anything with true intention.

## :active

This one just leaves me scratching me head. I mean, it's 2015, and a good amount of sites don't separate <code>:hover</code> interactions and <code>:active</code> ones. This is pretty simple, and pretty important to do. It's important because users should be shown that when they've clicked or tapped something. By clearly differntiating the <code>:active</code> action, we convey to them that the application got it, and is doing something. We can obviously take this much further to help the user, but that's beyond the scope here. By providing tangile, instant feedback, we remove the intial guesswork that comes with interacting with digital products. 

## :focus

This one is just a huge missed oppotunity to help our users out. By using our CSS reset, we often take this styling away and forget to add it back when we create our new styles. This is NOT okay though. The <code>:focus</code> styling is, arguably, the most important factor we have for helping our users out when interacting with our application. No one likes web forms, and as designers and developers we need to do whatever we can to mitigate these known paint points. By properly styling the <code>:focus</code> of a user on an element (especially form fields, but also hyperlinks for keyboard users), we can help **focus their attention** onto that element, which will reduce the mental load they have of trying to figure out how to do what they need to do.

## :visited

Last, but not certainly not least, is the <code>:visited</code> styling. Intended to help show your users which links they have visited before, and those which they have not.

## Putting it all together

Take this blog, for example: super stripped down, yes. But try hovering, clicking, focusing on a link: it's blatantly obvious, for each of these interaction types, that you've done something. The visual response is on par with your intention too, which is what we are really striving for. It all comes down to adding predictability to your site/app for your users: **don't make them feel uncertain about what will happen, or what they've done**.