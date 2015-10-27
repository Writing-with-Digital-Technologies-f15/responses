## Historicizing Content

###A Brief History
Since the 16th Century, when words first became mass-printable, there has been a need for typeface, and since about that time, printers have been expressing themselves with that form.  We even use the same system of sizing which was taken from the original, expressed as the amount of parts out of 72 which it was of a full inch. Fonts are still largely produced by foundries, which can justifiably be protective of their intellectual property, but more and more fonts are being produced by independent artists and typographers.

###Generic Font Families
Given a variety of fonts which had existed even since the beginnings of the personal computer, the early web needed a way for fonts to be categorized.  If a browser didn’t have, for example, a font used by the host, it at least needed a default of close-to-the-same, which it could translate into.
Description of each Font-family

Serif- These fonts are defined by their having serifs, or a “flaring, cross-stroke or other ornamentation (Daggett, 3.1) on the end of each stroke in the letter.  They tend to appear more formal and give their document or signage a more official feeling.
Sans-Serif- These are typefaces used without the serifs, which tend to be more plain and serve a variety of roles.
Cursive- belonging in this group is any font which has a “rolling” or “flowing” pattern in which letters connect or seem to almost connect to each other, and generally resembles handwriting.
Fantasy- Arguably the most wide-ranging of the generic families, fantasy ranges along a spectrum of any style which would not be included in any of the other families, and mostly for purposes of fun and amusement. 
Monospace- in this typeface, each figure takes up the same amount of space on a line, with m, for example, taking up the same amount of room as i. This makes the need for kerning less necessary, given that the spacing has been completely worked out within the typeface itself.  Often these fonts have the appearance of something that would appear on typewriters of old, and offer a formal style, leaning towards fun.
http://www.w3.org/TR/2013/CR-css-fonts-3-20131003/#font-kerning-prop

###@Font-face
@font-face- this CSS rule allows for the replacement of fonts with other fonts from different formats if the fonts which are being used are not found within the parameters of the browser being used.  This means that if a given font is not found, the site will be rendered with the next available font on the list (or re-set to the default of the given generic family, if none are found).  Each of these subsequent fonts can be retrieved from a different Open-source format, as long as the format itself is specified in the rule. 

@font-face also allows for the definition of composite fonts to a given site, if there is a need for some glyphs from a different alphabet in a font which doesn’t normally carry those glyphs.  In this case, the Unicode range must be defined for the character of that usage.

###Font Sources
Fonts are imported from a variety of open-sources.
-	TrueDoc
-	Embedded OpenType
-	Scalable Vector Graphics
-	TrueType/OpenType
-	WOFF (Web Open Font Format)
	
### CSS3 Fonts Module
This module was written by the W3C, and sets the rules and provides background for the decisions of all the coding for the font sets in HTML and CSS.  There is a lot to provide for, as many times fonts have to be adapted to different languages or different alphabets, and you can’t always get a perfect match.  In these cases, there is a font specification, but sites have a default form or the generic family available, which allows the appearance to be similar. For aspects such as style, some fonts do not have a specific setting for bold or oblique.  But there is a font-synthesis, which allows the weight of the font to be set and then act in place of one of those styles.  Font-face is a great system as well, which allows a different font entirely to be put in place for a specific element of a site, specifically an uncommon one which might need to be downloaded from another source for that purpose.  Overall it’s a really fascinating process through which characters (or “glyphs”) are translated into a font by the server, and in order to get the exact look across that you want, might take a good deal of planning and coding.

### Responsive Fonts
As more and more sites are being seen on different formats, everything from media to site grids themselves has to start thinking about creating more responsive options.  And fonts are no exception. There is a movement to create responsive fonts, which won’t conform to the traditional 100-900 weight scale of normal fonts.  Through new CSS coding, typographer Nick Sherman has put forward a proposal to create responsive font which would be able to expand and adjust with the size of the screen.  Citing previous programs such as Adobe’s Multiple Master font format from the 90s, adjustable fonts would give programs better-fitting content and headlines and take up even less data.
http://alistapart.com/blog/post/variable-fonts-for-responsive-design

Enter text in [Markdown](http://daringfireball.net/projects/markdown/). Use the toolbar above, or click the **?** button for formatting help.
