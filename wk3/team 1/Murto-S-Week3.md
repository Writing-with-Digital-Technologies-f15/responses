##How Did We Get Here?

This article explores the development of HTML to show how we ended up where we are today. It analyzes a discussion from the development of the image tag. Several developers shared various ideas for what they were implementing in their own browsers. Finally, a 'consensus' was reached by a developer who released their browser update first, and others followed their lead. 

After a while, the standards for HTML had reached a point where insurmountable revision was needed to further update it in its original form. A new rendition of HTML as XML, called XHTML, was attempted. However, XHTML ultimately failed, as its ultimate solution was to break sites that didn't perfectly fit its standards. Developers, who were used to the web just working, noted that this broke many older websites and therefore refused to properly use the XHTML standards.

Groups of browser developers alternatively collaborated to try and adjust their browser's HTML interpretation to work consistently like other browsers. These groups evolved the web standards by dissecting how each browser interpreted the code, and brought browser behaviors closer to a standard, while keeping backwards compatibility. Standards are still being developed today, but it seems that HTML will continue to be a retroactively inclusive language, while still accommodating the future. 

I have used this site at work to help encoding and displaying HTML5 videos on a website before (http://diveintohtml5.info/video.html), but I hadn't read this particular page. I found this line particularly interesting:

"...documenting the “forgiving” error-handling algorithms that browsers actually used. Web browsers have always been forgiving of HTML errors, **but nobody had ever bothered to write down exactly how they did it**." 

That is the primary reason I got interested in technical writing. I want to document the nitty-gritty stuff a developer know in their head, but never writes down. The program itself needs to be documented, not just how to use it. Otherwise, it totally can get complex enough that people need for form committees to figure out how their product even works.

## An Introduction to Browser Rendering

This video quickly explains how pages are rendered in the browser. It briefly introduces the DOM and CSSDOM, and then shows how the browser combines them to make a render tree. This creates the website's layout. It ends with showing on a timeline step-by-step calls to functions that the browser uses to visually put this data on the page for the user.

I thought this video was super interesting. My mind has always jumped from 'well, there's a DOM and then that appears on the page.' Seeing how everything is plotted out is interesting. I think it's easy to take some technology for granted as 'just working,' which I was certainly doing before.

## HTML and CSS - Intro

In the introduction to one of our textbooks, the book briefly overviews what various web technologies (HTML, CSS, Browsers etc.) are and how these technologies come together to make a website. It also demonstrates how websites are accessed. A browser is given a URL by the person using it. The browser then silently goes to a DNS lookup server to figure out which computer on the planet holds the information that should display at the typed in URL. The browser then talks to that specific computer, and gets the information on the website, and displays that for the user.

I don't have much to say about besides this: I never in my wildest dreams thought a book on HTML and CSS would start with how web servers work, so hats off to this book. Do people find this is useful information this early into learning web development?

## HTML and CSS - Structure

This chapter explains how the structures of digital, or even printed, documents can be related to a web document layout.  HTML is what is used to define this layout for a website, and HTML tags define how the text should display. There are also special tags that won't (usually) change how the page is displaying, but are still used to define a documents structure, like the head tag. The chapter concludes with tips you may want to consider if you're using a CMS or need to view the HTML for someone else's webpage.

While I am quite familiar with this information, I am reading the text as an example of excellent technical writing. Observing how it breaks down how attributes work or even the idea of comparing a word document to a website gives me tools to store in my belt for later. I think the books choice to depart from a normal textbook format (5) was a great benefit to it and I'm interested to see how it explains other concepts.

## HTML and CSS - Links

Links are how pages connect with one another. There are a variety of things you can do with a link: it can open in a new window, it can stay on the same webpage, it can go to a different website, or a different page on the current site. The text covers how these different actions can happen via code. It also overviews directory structures of websites and how various folders and files inside this directory structure affect navigation. The files in this directory structure can also access each other, by explaining which directories are their parents (containing them) or their children (contained by them).

Once again, I think the writing of this is excellent. However, I dislike the section on relative links because it leaves out key information. While relative links as described are useful if you are running a website without a server and URL, it is best not to use them as described on an actual server. If a file is moved for one reason or another, all of the relative links inside that file will break. To avoid this, it is best to write relative links as being from the root, like the following:

     <a href="/extra/link.html">Link</a>

Note the leading slash. 

This will always start looking for the file from the root directory of the website, instead of where the current file is located. But, as the textbook notes (84), that usually only works on a server. Putting a site on a server with relative links on it as described in the book is bad practice, and there should at least be a warning. I feel a mention of complications when files are moved should at least be discussed by the textbook considering it covers a lot of other things in detail.

