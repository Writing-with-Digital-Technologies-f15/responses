## Anotations

### CSS Fonts Module Level 3
http://www.w3.org/TR/2013/CR-css-fonts-3-20131003/
This module was written by the W3C, and sets the rules and provides background for the decisions of all the coding for the font sets in HTML and CSS.  There is a lot to provide for, as many times fonts have to be adapted to different languages or different alphabets, and you can’t always get a perfect match.  In these cases, there is a font specification, but sites have a default form or the generic family available, which allows the appearance to be similar. For aspects such as style, some fonts do not have a specific setting for bold or oblique.  But there is a font-synthesis, which allows the weight of the font to be set and then act in place of one of those styles.  Font-face is a great system as well, which allows a different font entirely to be put in place for a specific element of a site, specifically an uncommon one which might need to be downloaded from another source for that purpose.  Overall it’s a really fascinating process through which characters (or “glyphs”) are translated into a font by the server, and in order to get the exact look across that you want, might take a good deal of planning and coding.

### CSS Corner: Using the Whole Font
http://blogs.msdn.com/b/ie/archive/2012/01/09/css-corner-using-the-whole-font.aspx

This blog post by Sylvain Galineau is very instructive for the application of the features which are integral to all fonts.  What Galineau helps us keep in mind is that not all of the features are supported by every version of browsers which might be used on a regular basis.  What is important to keep in mind is the packaging format (such as WOFF or OpenType), because they determine which tags can be used with any font one might want to use on a given site.

## Historicizing Project
In my historicizing project, I am going to look at what it took to convert the fonts we’ve been using for the printed word into web-ready versions.  From what I have read so far there are aspects of coding fonts that I wouldn’t have thought of before.  These aspects affect how a specific font is coded to most closely reflect the author or designers intentions with a message.  But as we were seeing once again in Duckett, there are plenty of ways font sometimes needs to be manipulated for a sight to be more readable.

And yet fonts so often need much more than simply the letters and characters to convey the meaning. Font families are of course made up of the styles within a font, and the sizes of said font.  But in many cases there are ligatures, which need to be taken into account.  A ligature is a combination of letters which arise from whenever two letters in a word appear differently when paired together. 

I’ll also be exploring what has been done in order to allow for more fonts to be used in a web page and how the use of fonts is affected by different languages.  As most of us are aware, there are different alphabets used around the world.  But even within each specific alphabet there are ligatures and diacritic marks which allow for different letter usages and phonemes.

I’m looking forward to exploring all the different properties that a font can have, from weight, to style, to the generic families (which allow for a different, closely-related font to be used in a situation where the specified one does not work), and how these properties are allowing for adaptation across languages, devices and formats.





Enter text in [Markdown](http://daringfireball.net/projects/markdown/). Use the toolbar above, or click the **?** button for formatting help.
