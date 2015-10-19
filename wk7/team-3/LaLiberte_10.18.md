## SPAN Historicizing Structure
[Visual of structure](http://imgur.com/a/aviRA)

# What is SPAN?
- General definition: `<SPAN>` is a "generic character-level text container tag"
- Brief overview: uses
- Relationship with `<DIV>` [see last week]

#How SPAN came to be
[See last week for initial generic character-based container discussion]
- Benjamin Sittler, `<TEXT>` versus `<C>` versus `<MANY OTHER ELEMENTS>`, concerns about abuse
- Enter `<SPAN>`
- Internationalization (bidi languages, accessibility, other languages + print use)
- Still looking for sources on: specific point of origin for `<SPAN>` name, point at which `<SPAN>` usurped `<C>`

Note: The generic character-level container called `<SPAN>` was introduced between [draft 0](http://tools.ietf.org/html/draft-ietf-html-i18n-00) (15 August 1995) and [draft 1](http://tools.ietf.org/html/draft-ietf-html-i18n-01) (25 September 1995) of the _Internationalization of the Hypertext Markup Language_ IETF working draft. I've yet to find the discussion that lead to this addition in [W3's public mail archives](http://lists.w3.org/Archives/Public/), although I could just be searching the wrong listservs.

At this point, I’m stumped on how to find the first mention of `<SPAN>` in the w3 listserv. I’ve been exceedingly unimpressed with the search feature, and, after combing through various iterations of the listserv archives related to internationalization (also styled “i18n” for the eighteen letters between internationalization’s “i” and “n”), I’m pretty discouraged. It looks like, around the time <SPAN> would have been introduced, listservs began separating into different groups, and the archives for www-international@w3.org are lacking in `<SPAN>` development.

I’ll keep looking (and probably follow up with Chris on searching recommendations), because I’d really like to know the specific point of origin for the `<SPAN>` as an element title. This same discussion would likely also replace `<C>` with `<SPAN>`, so it would be nice to view the commentary on this change, especially considering how concerned some members were in the readability of the element name.

#SPAN today
- HTML5 and `<SPAN>`/`<DIV>` as catch-all elements and elements of last resort [see last week's discussion on "You can still use `<DIV>`]
- Use examples: `<SPAN>` used [as](http://www.w3.org/International/articles/inline-bidi-markup/ "SPAN with languages") [intended](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/span) versus `<SPAN>` by [the](http://stackoverflow.com/questions/1096251/what-is-span-span-element) [everyman](http://www.sitepoint.com/web-foundations/span-html-element/) [specific examples of this are WIP—looking at codepen, css-tricks]

##Questions for group
- **Does the definition-first placement make sense?** I think a cursory description of `<SPAN>` and what it does will help set readers up for the political discussion of what character-based selector element to use. A really solid definition would also clear up confusion on `<SPAN>` versus `<DIV>` and maybe take a detour into semantics. Pilgrim's "How did we get here?" was a little meandering, but I think his mix of specific examples and big picture ideas worked well.
- **Is there anything you think I'm missing?** Based on project guidelines, something that was mentioned last week but not this week...?


