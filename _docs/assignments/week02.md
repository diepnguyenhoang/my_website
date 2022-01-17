# 2. Project management

2nd day of week 1, I worked on configuring HTML, VCS (GITLAB, GITHUB) and started to get used to the documentation process.
To be honest, I did not get familiar with the term "documentation", because in my faculty, we usually use "learning journal" instead. Therefore, if you have similar feeling, you can think it simply as document or make diary of whatever you have learnt. 

## HTML, CSS, JavaScript
Normally, a website includes 3 main parts:

- HTML
> "The HyperText Markup Language, or HTML is the standard markup language for documents designed to be displayed in a web browser. It can be assisted by technologies such as Cascading Style Sheets (CSS) and scripting languages such as JavaScript."
[Wikipedia](https://en.wikipedia.org/wiki/HTML).

To create a basic website, all we need is a basic text editor (such as Notepad, or Notepad ++). Of course we can consider other applications including: Sublime text, Visual studio go, Brackets...

Once having a text editor installed in your laptop, we need to know about the [Anatomy of HTML elements] (https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Getting_started) (which look like syntax with heading and ending signal) and write what we want to show in our website.
I wrote my website in the Notepad ++ and named it "index.html"
![](../images/first-notepad.jpg)
![](../images/first-web.jpg)

- CSS
> "Cascading Style Sheets (CSS) is a style sheet language used for describing the presentation of a document written in a markup language such as HTML" [wikipedia] (https://en.wikipedia.org/wiki/CSS)

To create "style" for what we wrote, we need to have another text document featuring the styles we want. Here is some basic styles 
For example, I want my header will be in red. I will copy the rule in this [guidelines] (https://developer.mozilla.org/en-US/docs/Learn/CSS/First_steps/Getting_started) to new text document, and name it styles.css
> h1 {
  color: red;
}

To link the style to index.html, we need to write a rule <link rel="stylesheet" href="styles.css"> inside the <head> of our index.html
 ![](../images/second-notepad.jpg)
 ![](../images/second-web.jpg)

- JavaScript would not be our focus in this course.

So basically, a completed website as we have seen in front-end view contains: HTML (content and structure), CSS (style, e.g. colors, elements positions, and text sizes) and Javascript (provide interaction with the users).


## VCS (Version Control System) - Gitlab vs Github

- [Jekyll](http://jekyll.org)
- [Google](http://google.com)
- [Markdown](https://en.wikipedia.org/wiki/Markdown)

## Code Example

Use the three backticks to separate code.

```
// the setup function runs once when you press reset or power the board
void setup() {
  // initialize digital pin LED_BUILTIN as an output.
  pinMode(LED_BUILTIN, OUTPUT);
}

// the loop function runs over and over again forever
void loop() {
  digitalWrite(LED_BUILTIN, HIGH);   // turn the LED on (HIGH is the voltage level)
  delay(1000);                       // wait for a second
  digitalWrite(LED_BUILTIN, LOW);    // turn the LED off by making the voltage LOW
  delay(1000);                       // wait for a second
}
```

## Gallery

![](../images/sample-photo.jpg)

## Video

### From Vimeo

<iframe src="https://player.vimeo.com/video/10048961" width="640" height="480" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe>
<p><a href="https://vimeo.com/10048961">Sound Waves</a> from <a href="https://vimeo.com/radarboy">George Gally (Radarboy)</a> on <a href="https://vimeo.com">Vimeo</a>.</p>

### From Youtube

<iframe width="560" height="315" src="https://www.youtube.com/embed/jjNgJFemlC4" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>

## 3D Models

<div class="sketchfab-embed-wrapper"><iframe width="640" height="480" src="https://sketchfab.com/models/658c8f8a2f3042c3ad7bdedd83f1c915/embed" frameborder="0" allow="autoplay; fullscreen; vr" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>

<p style="font-size: 13px; font-weight: normal; margin: 5px; color: #4A4A4A;">
    <a href="https://sketchfab.com/models/658c8f8a2f3042c3ad7bdedd83f1c915?utm_medium=embed&utm_source=website&utm_campaign=share-popup" target="_blank" style="font-weight: bold; color: #1CAAD9;">Dita&#39;s Gown</a>
    by <a href="https://sketchfab.com/francisbitontistudio?utm_medium=embed&utm_source=website&utm_campaign=share-popup" target="_blank" style="font-weight: bold; color: #1CAAD9;">Francis Bitonti Studio</a>
    on <a href="https://sketchfab.com?utm_medium=embed&utm_source=website&utm_campaign=share-popup" target="_blank" style="font-weight: bold; color: #1CAAD9;">Sketchfab</a>
</p>
</div>
