#The 90s Polyfil - A tale of terror 

There are people working for many years to create the standards that all of us need, in order to perfect our toolset. One result of such efforts is the draft known as <b>Web Components</b>.

And then, there are people who take all those efforts and use them to bring chaos and revive our worst nightmare and an era dominated by neon lights and Comic Sans. Let me introduce you to <b>The 90s Polyfil</b>.

Ever worked in the 90s? What is your opinion about blinking text, obstrusive popups welcoming you to the page or snappy under construction animated images? If you miss those times and you wish that you could use all those cool and awesome tools today, but you don't know how, <b>The 90s Polyfil</b> is exactly what you need!

##The bitter truth
The truth is, that there are no maniacs, trying religiously to bring the 90s web into our lives again. The 90s Polyfil is not about that. It's about providing fun and simple examples for those who want to start working with Web Components, but while trying, they face problems and can't find more information. Each of the Web Components here, shows something different that you can do.

Exactly because this is not meant to be used in any real website, all elements created are meant to work only on the latest Chrome, with the HTML Imports enabled (it's a flag), and they use no polyfil.

##Custom Elements
### 90s Welcome
A very simple custom element. Anything you put inside the element, becomes an alert box.

####Things that you can learn by reading the code
- How do you register a custom element
- How do you use html imports
- How do you cope with unstyled content, while the element is being registered?
- How do you use the equivalent of the "onload" event.

####Usage
```html
<nineties-welcome>Hello there, Nikos!</nineties-welcome>
```

### 90s Under Construction
Show an "Under Construction" animated icon, along with some custom text.

####Things that you can learn by reading the code
- Everything included in the 90s Welcome element
- How to render content from a template
- How to access elements inside an imported document
- How to write styles specific for a template's contents
- How to add nodes in the Shadow DOM

####Usage
```html
<nineties-under-construction>This page is under construction!</nineties-under-construction>
```

### 90s Spacer
_Not implemented yet_

### 90s Blink
_Not implemented yet_

### 90s Marquee
_Not implemented yet_

