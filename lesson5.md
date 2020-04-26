## Structure Webpages with HTML

### Notes From Duckett Ch. 18

Questions to ask when making a website:
> - Who is the target audience?
- Can you collect information on who visits your website?  This may help you tailor your site to thier interests. 
- Why are they visiting?  For what purpose?
- How frequently will they visit?
>
Additionally, make a *site map* (See pages 461-462 of Duckett).  Site maps can be organized using a _wire frame_ model, which is similar to a rough sketch of what the website will look like.  

#### How can a designer make text stand out?
Variations with:
  - color 
  - size
  - style 

____________________________________________________________________________

__Visual__ hierarchies are also useful.

As are images ![](https://d15shllkswkct0.cloudfront.net/wp-content/blogs.dir/1/files/2020/03/rocket-1103713_1280.jpg) :rocket:  

__Grouping__ is also a method of catching a readers attention.  By sorting information in certain ways, the designer can shepard the website user through the website (Duckett, 469).
>  This can be achieved by using techniques such as proximity, closur, continuance, white space, color, and borders.  
>
Having user-friendly __navigation__ is also an important.

____________________________________________________________________________

## Information relation to HTML web-design

HTML webdesign should be smooth.  If it is designed well, it should read like a good news article or novel; that is, it should be clear, easy to follow (ok maybe not all novels), logical, and to-the-point.  

**For example**
> <html>
    <head>
        <title>MAIN PAGE</title>
    </head>
    <body>
        <h1>This is the first header of the body page</h1>
        <p>anything within the body of a web page is displayed in the main browswer window.</p>
    </body>
</html>


(Duckett, 27)

Notice how in the above **example** each bracket has a corresponding bracket.  `<html> corresponds with </html>`, for example. A useful tip for writing HTML code is to start that every time you start one `<>`, make the corresponding `</>`, so that you do not forget to include it at the end of the code.  THis will make the writing process a bit more smooth, potentially.  

Mac v Windows
- each technology has its own unique application for manufacturing websites. 
- Mac uses "Textedit"
- Windows uses "NotePad"
- once the applicaiton is open, the process is fairly similar.  It involves writing code similar to the above **example**

____________________________________________________________________________

## Chapter 8

HTML text have...
- ID attributes, (`<p id-"pullquote">...</p>`);
- class attributes (`<p class-"important admittance">`);
- block elements (signified with `<ul>...</ul>` and they sometimes included bulleted lists, which are signified by `<li>...</li>`);
- inline elements, whose characteristics range.  They include `<b> BB </b>`, `<em> EM </em>`, and other symbols;
- Grouping text and block elements in a block. This is achieved with the `<div> HEADER </div>` function;
- iFrames.  These are useful devices that are often used to place another source, such as a advertisment, into the website. 

### Meta data

This includes things that are important to a website but are not visible to the user. EX: `<meta name="description" content="lesson5" />`  Notice that the bracket starts with `<meta`, has the data in the middle, and ends with `/>`. 
- description
- keywords
- robots -- `"follow"` `"nofollow"` 
- author
- pragma
- expires 

### Escape Characters

THere are *special* characters, not like Frodo and Gandalf, but like Ampersand and Trademark, that are available in markup.  

&amp; is produced by `amp&;` 
&copy; is produced by `&copy;`
&pound; is produced by `&pound;`
and [so on](https://www.freeformatter.com/html-entities.html)



Designers can add comments in their code by writing `<!-- comment -->`

____________________________________________________________________________

## Chapter 17
- HTML 5 reduced the amount of code needed to write websites, making the coding for websites simplier and more concise.  For example, instead of having to write `<div id="header">` designers can now write `<header>`.  It requires less code.  

- navigation bars can be written using the `<nav>` code, which can be be further supplemented with `<ul> and <li>`.

- `<articles>` can "act as a container for any section of a page that could stand alone and potentially be syndicated," according to Duckett.  
- `<asides>` have "two purposes, "according to Duckett.  If the aside is within an article, then could contain corollary information that is not directly relevant to the article.  If the aside is outside of an article, then it might inlcude things like links to other parts of the website, a search box, or tweets.  
- `<sections>` denotes content that is grouped together such as news, photos, or various other items.  
- `<hgroup>` groups 1 though 6 headings together so that they are listed as one heading. Each sub-heading is written out like `<h1> or <h2> ... <h6>`
- `<figures> and <figure captions>` are used to describe an image.  The caption function acts as a caption for the figure.  
- `<div>` the div element can be used when there is no suitable element group.  It can, for example be used as a "wrapper" (Duckett, 440). 
- `<a> ...content ... </a>`turns the middle content into a link. 
