---
title: Obligatory First Post
author: 'Alex Axthelm'
date: '2024-06-20'
slug: []
categories: []
tags: [start, meta, blogdown, hugo]
type: ''
subtitle: ''
image: ''
---

I guess this is my first post.

Neat.

Most of the first posts I've seen are either long-winded manifestos declaring the author to be an expert on everything under the sun, or a record of setting up the blog itself.

So keeping in the better of those traditions:

This isn't the first time I've tried setting up a blog, but this is the first version that has non-trivial content (this post, at the very least) visible at `alexaxthelm.com`.
Setting everything up went pretty smoothly this time around, probably because I've learned a lot since I last tried 😆.

Overall, setting everything up, and making it accessible took a few hours in the evenings over the course of a week or so.
Roughly:

- Getting `blogdown` running with the default site: *~10 min*
  - Excellent documentation
- Picking a theme *~1 hour*
  - I knew this was going to be a distraction for me (based on the past iterations of this project), so I set myself a time limit to browse the themes.
  - I picked [Beautiful Hugo](https://github.com/halogenica/beautifulhugo), which is pretty nice looking out of the box, and the site-specific config was pretty easy. Also excellent documentation.
  - Previous versions of the blog used [Future Imperfect](https://github.com/jpescador/hugo-future-imperfect), and I see [this version](https://github.com/pacollins/hugo-future-imperfect-slim) which is archived, but also still updated more recently than the original theme.
- Integrating theme, changing `config.toml`, writing [About](../../page/about.md) and [colophon](../../page/colophon.md) *~1 hour*
- Making some test posts *~10 min*.
- getting a rendered site into a repo on GitHub *~5 min*
- Launching `main` at [`https://namingthingsishard.netlify.app/`](https://namingthingsishard.netlify.app/)
- Getting deploy previews to work *5 min*
  - Needed to have the Netlify integration set up before I made the PR.
- Realizing that I should have `public/` in my `.gitignore` *like 2 hours over 3 night*
  - ⚠ Do this earlier next time.
  - The real kicker is that I had put all the `.html` files in my `.git/info/exclude`, so I didn't see the exclusion on GitHub.
- Transferring the DNS records from my old blog to this one ~30 min
  - I was using Netlify for that too, but not Netlify DNS.
  - I released the domain name on the old site (and let it lapse back to a `*.netlify.app` site), then deleted site and closed account
  - The docs for using an external DNS for Netlify are outdated, but getting started with Netlify DNS just sort of worked? Cool I guess; feels weird though.
- Writing this post *~45 min*
  - Writing docs always take longer than you think.

Alternately, setting this up took a longer time, over the course of several years.
What I had already:

- GitHub account
- Working knowledge of R and git
- Domain name through [Hover](https://hover.com/)

Overall, it wasn't that hard, and I'm sure that if I need to do it again, it will go smoother next time.
