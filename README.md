# TL;DR
LaTeX offers superior control over document preparations with the added beautiful visualizations. For those interested, you need to download two components:
- A LaTeX compiler (such as **MikTeX**)
- An appropriate text editing document (such as **Texmaker**)
- The [LaTeX project](https://www.latex-project.org/get/) has information for installation for all operating systems. But! The [video installation guides](#installation) below are easier to follow.

Once you have these components downloaded, there are practice documents to get you started in the [\test-file](https://github.com/mrsunny0/LaTeX-intro/tree/master/test-files) folder in this repo. If you are an MIT student, in particular in the Bioengineering department, you can our other repos to write your thesis [proposal](https://github.com/mrsunny0/LaTeX-thesis-proposal) or [defense](https://github.com/mrsunny0/LaTeX-thesis-defense) documents.

For those who want to _skip a local installation_ of LaTeX, you can use a cloud-based LaTeX enviornment called [Overleaf](https://www.overleaf.com/) which provides all the tools needed to code, compile, and visualize LaTeX. A more detailed description can be found [below](#using-).

# Table of Contents
- [TL;DR](#tl-dr)
- [Getting started](#getting-started)
- [Setting it up](#setting-it-up)
  * [Installation](#installation)
  * [Practice](#practice)
- [Using Overleaf](#using---overleaf--https---isenefileswordpresscom-2016-09-overleafpng-w-125-)
- [Takeaway](#takeaway)


# Getting started
![equation](http://latex.codecogs.com/gif.latex?%7B%5CLaTeX%7D) (LaTeX) has been the de-facto scientific writing software for publications in engineering, social sciences, and formal document preparations. LaTeX is a compiled typsetting language, meaning that code such as `\textbf{XYZ}` needs compiled to generate **XYZ**. Whereas, programs such as Word use formatted text, often known as WYSIWYG ("what you see is what you get") where the word processor uses commands from icons and GUI's (graphical user interface) where bolded text are literally bolded in the document.

LaTeX is (in)famously known to give users comprehensive control over their documents, whether that is formatting, text manipulation, graphics, and overall visualization. However, that comes with a rigorous learning curve which programs such as Word have tried to minimize. Below is a table comparing the utility and function of LaTeX versus Word.

| LaTeX | Word |
| --- | --- |
| Comprehensive control over document style/structure | Document style/structure is fragmented among numerous buttons, icons, and GUIs |
| Formatting is compiled, which requires an extra step to visualize a document | Changes and formatting are visualized immediately |
| Figures, captions, and tables can be organized neatly and programmatically | Placing figures, captions, and tables require some manual placement and mouse work |
| Large documents can be easily broken down in an organized and hierarchical way | Managing large documents can be cumbersome |
| Overall formatting styles can be adjusted with single line edits in the code | Overall formatting changes are done manually, with ctrl+F and replace, or using the styles tab |
| LaTeX requires downloading multiple components to run; but is free | Word works out of the box; is not free |  

# Setting it up
There are two pieces to setting up LaTeX on your local computer
* A LaTeX  **compiler** (specific for either Windows, Mac, or Linux). \
  This takes what you write, and converts it into a clean and professional document.
* A **text editor** to write your code. Highly recommended is to use a LaTeX IDE (integrated development environment) where you can type and compile your code in one software enviornment. A direct analogy is like using Word, where you have access to commands and visuals for rendering your code/document.

## Installation
* LaTeX  compiler
	- PC: [MikTex](https://miktex.org/download)
	- Mac: [MacTex](http://www.tug.org/mactex/)
	- LInux: [TeX Live](https://www.tug.org/texlive/)
* LaTeX  IDE (in order of _my_ preference)
	- [TeXmaker](http://www.xm1math.net/texmaker/)
	- [TeXstudio](https://www.texstudio.org/)
	- [TeXworks](http://www.tug.org/texworks/) (this is automatically installed with most TeX compiler installations)

Downloading the appropriate softwares to get LaTeX running on your computer is straightforward. However, in my experience, many users tend to become dissuaded when they realize they haven't downloaded _all_ of the components, get lost in confusion, and never return to LaTeX without even touching the actual program. To avoid this hassle, please refer to installation videos, courtesy of YouTube.

* For windows: [both MikTex \& Texmaker](https://www.youtube.com/watch?v=yPnfHRE_W_g&t=1056s)
* For mac: [mactex](https://www.youtube.com/watch?v=XlxiytGeWds) \& [Texmaker](https://www.youtube.com/watch?v=-KgxKA-UBh4)
* For linux (ubuntu): [both TexLive \& Texmaker](https://www.youtube.com/watch?v=Q2SBoeCJB3Q)

## Practice
You can find practice files under [./test-files](https://github.com/mrsunny0/LaTeX-intro/tree/master/test-files) where you can check your installation by running a standard _Hello World_ example, to more advanced topics such as placing figures, tables, and breaking down your document into modular parts.

Other links to great tutorials are:
* LaTeX [Wiki](https://en.wikibooks.org/wiki/LaTeX)
* Overleaf [tutorials](https://www.overleaf.com/learn/latex/Tutorials)
* ShareLaTeX [tutorials](https://www.sharelatex.com/blog/latex-guides/beginners-tutorial.html)
* LaTeX [templates](https://www.latextemplates.com/)

# Using ![overleaf](https://isene.files.wordpress.com/2016/09/overleaf.png?w=125)
[Overleaf](https://www.overleaf.com) is a great cloud-based tool where the overhead for installing, compiling, and arranging your LaTeX files are done via a web-app. The Overleaf platform is very popular for its user-friendly interface, and as an educational tool to familiarize students with LaTeX code without bogging them down with operating system and computer specific installations and paths.

Note that the more fitting name **ShareLaTeX**, a similar platform to Overleaf, has been merged with Overleaf and is no longer developed. So if you do decide to work on a web-based LaTeX platform, mostly all attention is being focused on Overleaf. Given Overleaf's popularity as a web-based LaTeX platfrorm, it does come with benefits and setbacks versus a traditional local (personal) installed platform.

| Overleaf (web-based) | Local Installation |
| --- | --- |
| Need Wi-Fi | Works anytime |
| All files, figures, and file structure needs to be uploaded and organized via Overleaf | Control over files and file structure is local; however, you need to be mindful of where your files are stored |
| No installation required, and Overleaf has comprehensive tools and tutorials for beginners | There is a significant startup cost to getting LaTeX running locally |
| Documents can be easily shared via url links; however, your documents, figures, and potentially sensitive data will not be private | You maintain your own privacy and sharing |
| Overleaf may get slower with larger documents, especially with slow internet speeds | Your as fast as your computer allows |
| Some tools, tricks, and packages are still unavailable in Overleaf | All tools, tricks, and packages are intended to work on local LaTeX distributions |

## Takeaway
Personally, my opinion is that Overleaf is a great tool for beginners who want to learn and create short documents for classes and assignments. However, for larger documents such as papers, thesis, and sensitive materials such as legal documents should be written via a local installation of LaTeX.
