
I started this assignment by playing with the pure.CSS framework. I figured I could see what that framework could do, and then I would recode the website as close as I could without a framework. I chose pure.css because I had used bootstrap before, but pure.css was new to me. 

I mostly just used the Grids feature (http://purecss.io/grids/) to position elements on the page. I didn't really set out with a goal, I just wanted to see what it would do. Unfortunately, what is did most of this time was this:

![screen shot 2015-09-24 at 2 03 23 pm](https://cloud.githubusercontent.com/assets/7316321/10083730/6303c916-62c5-11e5-9667-203455165eef.png)

The site works when the cell size is set to class="pure-u-3-8" but does that at class="pure-u-2-8", which should be one size slightly off. It either did that, didn't change, or worked. I tried reading a different tutorial, but still couldn't make much sense out of it.

I don't really understand pure.css grids. I got the website to have a decent layout, but it was a lot of guesswork and number picking. I still don't understand why it goes from 'the text is fine' to 'the text is overlapping' so quickly.

After that, I applied some of my own CSS to 'wrap up' the layout: set the background color, centered the page, set the link color. I didn't see anything in the pure.css documentation that indicated it did those things, but I might have been wrong.

I then copied my file, stripped out all of the pure.css code and tried to match the way the site looked with plain CSS. I got decently close. I almost think that looks better than the text getting really narrow. Since I already have a decent grasp on CSS (though I'm no web designer), this step wasn't too difficult. 

From this, I learned the benefits of using pure.css. It's requires very little extra code and it is nice that it doesn't use JavaScript. Bootstrap requires JavaScript and, at least when I used it, is a bit less flexible. If I really threw myself into pure.css, I bet it has more flexibility and customization than Bootstrap since it's just CSS. 

I feel CSS touches on cultural issues as we expect documents to have an organization to them, and that organization usually isn't what would be delivered by plain HTML. Plain HTML will provide a straight-down layout, the text would get wider than a user is culturally used to, and sometimes the font size wouldn't be appropriate (for example, footnotes shouldn't be the same size as the text). CSS gives us the tools to make these layouts match cultural expectations, and responsive CSS (as provided by pure.css) let that continue to happen on screens of various sizes.
