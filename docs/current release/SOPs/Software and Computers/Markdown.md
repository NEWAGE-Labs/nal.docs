# Standard Operating Procedure - Markdown

>Most recently edited by: *Paul VanderWeele*  
>Most recent edit date: *Jan 19th, 2021*  
>Edits were authorized by:  

## Table of Content

[Purpose and Scope](#purpose-and-scope)  
[Terms and Definitions](#terms-and-definitions)  
[Usage](#usage)  
[Syntax Guide](#syntax-guide)   

## Purpose and Scope

The purpose of this procedure is to demonstrate how to use the Markdown syntax to enrich text to include bolding, italicizing, headers, tables, hyperlinks, and other formatting features without the bulk and complexity of a XML-style document like [Office 365's Word Processor](Office 365.md). Markdown is used to format the documentation on the [NAL Documentation Server](Servers.md).

## Terms and Definitions

###### Raw Text

> Raw Text is computer encoded bits that correspond with human readable characters only. These characters can be from any language, and can represent numerals, punctuation, or whitespace.

###### Raw Text File

> A Raw Text File is a indexed file on an operating system consisting of only [raw text](raw-text) like a .txt, .csv, or .md file. This excludes XML-based documents like Microsoft Word's .Doc and .Docx formats.

###### Local IP Address

> A Local IP Address is a number correlated by the office router to correspond with the MAC Address of a computer on the local network.

## Usage

#### Adding Markdown
Adding Markdown syntax to text is very straight-forward as the formatting is text itself. Markdown is kept as [raw text](#raw-text) in files with a **.md** extension indicating it is a Markdown file. Markdown files can be created or edited in almost any [raw text editor](#raw-text-editor) like [Notepad](Notepad.md) or [Atom](Atom.md), and should contain ONLY Markdown content.

#### From Markdown to HTML.

 However, without another program, the text does not actually look formatted. An extension exists for [Atom](Atom.md) that allows it to display formatted Markdown within the editor; however this is primarily useful only for personnel that are *editing* documents. The published and controlled version of the document is rendered using an interpreting program. We use the interpretter [MkDocs](MkDocs.md) to convert the Markdown syntax into [HTML](HTML.md). The formatting web documents are then served on the [NAL Documentation Server's](Servers.md) local IP address.

#### Version Control

Because Markdown files are [raw text](#raw text), every bit of information can be broken down into rows and columns. We use the version control system [Git](Git.md) to keep track of each change made to Markdown files, including exactly which rows and columns were edited, what they were changed from and to, who changed them, what date/time they changed them, and notes about each change.

## Syntax Guide

#### Headers

```{.md}
# This is an <h1> tag
## This is an <h2> tag
###### This is an <h6> tag
```

#### Emphasis  

```{.md}
*This text will be italic*  
_This will also be italic_  

**This text will be bold**  
__This will also be bold__  

_You **can** combine them_  
*You __can__ combine them*  
```  

#### Lists

###### Unordered

```{.md}
* Item 1  
* Item 2  
  * Item 2a  
  * Item 2b  
```

###### Ordered

```{.md}  
1. Item 1  
1. Item 2  
1. Item 3  
   1. Item 3a  
   1. Item 3b  
```  

#### Images

```{.md}  
![Some Image](/images/some image.png)  
Format: ![Alt Text](url)  
```  

#### Links

```{.md}
https://newagelaboratories.com -- automatically makes link  
[NEWAGE Labs](https://newagelaboratories.com) -- Use [text](url) format to replace text.  
```  

#### Blockquotes

```{.md}  
As we mentioned in our previous email:  

> This was a waste of time  
> and we are not at fault.  
```  

#### Code

###### Inline

```{.md}  
Use the `SUM()` command in Excel to add two numbers.  
```  

###### Blocks

````{.md}  
To write this syntax guide, we used code blocks like this:  


## Headers  

```{.md}  
# This is an <h1> tag  
## This is an <h2> tag  
###### This is an <h6> tag  
```  

The 3 backticks ``` indicate the beginning and end of the code block.  
Additional backticks may be used. This allows ``` to be typed within the code block.

Optionally, a language can be specified on the first line.  
Use the {} notation to indicate a language besides the default (Python).

````  
