<div align="center">
  <a href="https://www.microsoft.com/en-us/">
    <img src="https://skillicons.dev/icons?i=windows&theme=dark"/>
  </a>
  <a href="https://github.com">
    <img src="https://skillicons.dev/icons?i=github&theme=dark"/>
  </a>
    <a href="https://git-scm.com">
    <img src="https://skillicons.dev/icons?i=git&theme=dark"/>
  </a>
</div>
<h3 align="center">CMD CheatSheet for Windows and Github/Git</h3>

<hr>

This document contains a short compilation of commands to use on **CMD**(command line) for both **Windows** and **Github**.

<h3>NOTES:</h3>

  >This is not a extensive list of all commands for both Windows and Github/Git.
	
  >All Windows commands work as intended on Windows 11 but I can't confirm on Windows 10 and prior versions.

<hr>

<div align="center">
  <a href="https://www.microsoft.com/en-us/">
    <img src="https://skillicons.dev/icons?i=windows&theme=dark"/>
  </a>
</div>


# Files and Folders Management 

	> To start syncing your workspace, just sign in with Google in the menu.

- The file synchronization will keep one file of the workspace synced with one or multiple files in **Google Drive**, **Dropbox** or **GitHub**.
	> Before starting to sync files, you must link an account in the **Synchronize** sub-menu.





# Publication

Publishing in StackEdit makes it simple for you to publish online your files. Once you're happy with a file, you can publish it to different hosting platforms like **Blogger**, **Dropbox**, **Gist**, **GitHub**, **Google Drive**, **WordPress** and **Zendesk**. With [Handlebars templates](http://handlebarsjs.com/), you have full control over what you export.

> Before starting to publish, you must link an account in the **Publish** sub-menu.

# Markdown extensions

StackEdit extends the standard Markdown syntax by adding extra **Markdown extensions**, providing you with some nice features.

> **ProTip:** You can disable any **Markdown extension** in the **File properties** dialog.


## SmartyPants

SmartyPants converts ASCII punctuation characters into "smart" typographic punctuation HTML entities. For example:

|                |ASCII                          |HTML                         |
|----------------|-------------------------------|-----------------------------|
|Single backticks|`'Isn't this fun?'`            |'Isn't this fun?'            |
|Quotes          |`"Isn't this fun?"`            |"Isn't this fun?"            |
|Dashes          |`-- is en-dash, --- is em-dash`|-- is en-dash, --- is em-dash|


## KaTeX

You can render LaTeX mathematical expressions using [KaTeX](https://khan.github.io/KaTeX/):

The *Gamma function* satisfying $\Gamma(n) = (n-1)!\quad\forall n\in\mathbb N$ is via the Euler integral

$$
\Gamma(z) = \int_0^\infty t^{z-1}e^{-t}dt\,.
$$

> You can find more information about **LaTeX** mathematical expressions [here](http://meta.math.stackexchange.com/questions/5020/mathjax-basic-tutorial-and-quick-reference).


## UML diagrams

You can render UML diagrams using [Mermaid](https://mermaidjs.github.io/). For example, this will produce a sequence diagram:

```mermaid
sequenceDiagram
Alice ->> Bob: Hello Bob, how are you?
Bob-->>John: How about you John?
Bob--x Alice: I am good thanks!
Bob-x John: I am good thanks!
Note right of John: Bob thinks a long<br/>long time, so long<br/>that the text does<br/>not fit on a row.

Bob-->Alice: Checking with John...
Alice->John: Yes... John, how are you?
```

And this will produce a flow chart:

```mermaid
graph LR
A[Square Rect] -- Link text --> B((Circle))
A --> C(Round Rect)
B --> D{Rhombus}
C --> D
```

## Biliography

-  <a href="https://training.github.com">Oficial Github/Git CheatSheet</a>
- <a href="https://training.github.com">Oficial Windows CheatSheet</a>
- <a href="https://skillicons.dev">Icons</a>