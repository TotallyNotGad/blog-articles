A long overdue blog

---

So, ive been wanting to practice writing for a while now, and im finally giving myself a set schedule to hold to. 
One ’thing’ a week, be it an explainer article, a project update, or just me rambling into the void.

This blog is empty right now, just a hollow clone of my ‘advertiser friendly’ site

I have a few ideas on what to write about, and a few drafts allready in  the works, but im hoping this will finally be the push for me to get  onto a consistent schedule (i say for the thousandth time)

No plans for punishment if i fail, or end time for this project, just go for as long as I can.

Not going to be too strict about it either, if I (somehow) write a 4 part  series, im not going to spread it out over a month just to meet the arbitrary standard.

No minimum word count, just ’enough’ by my own self-imposed standards.

(Im totally counting this as the first weeks ’thing’)

,,, Ok thats not ’enough’ even by my loose standards. So how about we get even more meta?

# How This Blog Works

Its hosted on Github Pages because the free domain looks slightly better  than Netlify’s, but it means i have to deal with Github Actions,  :face_puking_emoji:

The pages are generated using Hugo Templates, but none of the contents are stored in the sites repo. 
The projects tab uses the Github api to get the names, descriptions, and READMEs of all my pinned projects,
and converts them into a markdown page for Hugo to read. The little author blurb at the top is made from my Github profile too.

The blog section is made from an Obsidian vault stored in a git repo, it gets cloned in during build and ob-to-hugo converts it into more standard markdown.

I designed it this way mostly because i wanted to avoid duplicating the project descriptions on my Github profile. And nesting an Obsidian vault into a Hugo project felt extra weird

I also hoped to reuse as much code as possible between this and my other site, but thats going badly right now due to Github actions being weird as allways.

Im planning on moving away from Hugo actually, and just using plain Jinja templates, so maybe ill write a more in depth explanation of how this whole mess works after that.

I think thats enough writing for now, better post this before i chicken out.

