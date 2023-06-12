# Learning Markdown

## What is Markdown and why should I use it?

Markdown is a kind of lightweight mark up language. It is used to format plaintext documents. Instead of using an application such as word to format elements and see instant changes (which can be done by cicking buttons such as the 'bold button'), you can use the Markdown language instead. With Markdown, you use different symbols or "syntax" to specify which text you would like to change or look a certain way.

It is worth using because it can be used for practically everything, including websites, documents, email, presentations and even when publishing books!

Markdown is futureproof because it isn't specific to any one application which could eventually shut down - which could result in you losing your work. It can be used on any device, any operating system and across multiple platforms meaning you will always be able to read your Markdown-formatted text.

We are now going to look at some of the syntax required to make changes in Markdown.


## *Headers*

To create headers in Markdown, you can use a hashtag (#) followed by a space and your text with the number of hastags corresponding to the html header number. For example a h1 header would use one hastag and a h2 header would use two hashtags all the way up to a h6 header or 6 hashtags.  
*Note: Do not forget the space after the hastag ir it will not work!*

Example:

# This is a h1 header  


## This is a h2 header  


###### This is a h6 header



## *Paragraphs and Line Breaks:*

To start a new line or use a line break, you need to leave spaces at the end of the line/ text, like this...  
Here is a line break.

You can also make a line break by using the br html tag.<br>
Like this.

To make a new paragraph, you must leave a line between your text/paragraphs.

Example:

Here is a paragraph.

Here is a second paragraph.

This is the first line of my third paragraph.  

## *Ordered and Unordered Lists:*

There are a choice of three symbols (or syntax) you can use to create an unordered list (aka bullet points). These are a single asterisk (*), a single dash (-) or a single plus symbol (+) followed by a space. See the examples of each below:

- here
- are
- dashes
 

* here
* are
* asterisks


+ here
+ are
+ pluses
 

You can indent to have a sub list/nest items but leaving two spaces before adding the symbol. See the example below using dashes.

- you
- can
  - also
  - indent
  - by using two spaces and your symbol/syntax
    - further indent
    - to nest further
      - using two spaces
      - each time

Use numbers followed by a period to make an ordered list. It doesn't matter which numbers you use, as long as you start with 1.  

1. Here
2. is
3. an
4. example


1. You
2. can
3. make
   1. sub
   2. bullets
   3. also by double spacing then using numbers from 1 again.
4. like
5. this

- You
- can
  1. mix
  2. and
  3. match
- the type
- of lists
- when indenting
  - or
  - indent
    - further
    - by using an
    - additional two spaces

## *Bold and Italics:*

**You can use asterisks at the start and end to bold words.**  
__You can also use underscores to bold text__  
It is better to use **asterisks** when bolding in the middle of a word such as ha**pp**y.

*Use one asterisk at the start and end to make your text italic.*  
_or you can use a single underscore._
Using a single asterisk is best for using italics in the m*idd*le of the word.

***Use three asterisks to make text bold and italic.***  
___You can also use three underscores.___  
Use three asterisks to make the m***idd***le of a word bold and italic.

## *Adding a Link:*

To add a link, use square brackets []to put your text in and then add your link in parenthese ().

Syntax Example:  

[display text here](link-url)

Actual Example:

Here is a link to [Google](https://www.google.co.uk/)

## *Adding an Image:*

To add an image, use an exclaimation mark, followed by your alt text in square brackets []. You would then add the path/Url of your image in parentheses (). If you want, you can include a "title" in speechmarks within these.

Syntax Example:  

![alt](image url/path "can include title")

To add a link to the image, enclose the above in square brackets and then follow with your link in parenthese.  

Actual Example:

![A dog with sunglasses](https://images.pexels.com/photos/2607544/pexels-photo-2607544.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1 "Medium Short-coated White Dog on White Textile")  

## *Adding an Image With a Link:*

To add a link to the image, enclose the above in square brackets and then follow with your link in parenthese.  

[![alt](img url/path)](link url)

Example:

[![A dog with sunglasses](https://images.pexels.com/photos/2607544/pexels-photo-2607544.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1 "Medium Short-coated White Dog on White Textile")](https://www.pexels.com/photo/medium-short-coated-white-dog-on-white-textile-2607544/)

---