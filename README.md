# Lulu's World 🌺

Lulu's personal website, with an island theme: a starry night sky, ocean waves, warm sand and surfboard-shaped links. It's a place to show off her hobbies, her bracelet business and her videos.

## What's on the site

| Page | File | What it's about |
|---|---|---|
| Home | `index.html` | Welcome page with surfboard links to everything else |
| Gymnastics | `gymnastics.html` | Skills, goals and proudest moments |
| Choir | `choir.html` | Performances and favorite songs |
| Bracelet Shop | `bracelet-shop.html` | **Beadiful Chaos** bracelets, prices, how ordering works and where the money goes |
| Director's Studio | `directors-studio.html` | Her videos and what she wants to film next |
| All About Me | `all-about-me.html` | Favorite things, fun facts and dreams |

## Meet Pua

Pua is Lulu's plushie helper: a fluffy blue monster with little horns and a hibiscus flower. She appears on every page, answers visitors' questions and plays an original island music loop.

- When the site is opened as a Claude artifact, Pua uses Claude to answer, with strict kid-safety rules and only the facts she's been given.
- Everywhere else (like GitHub Pages), Pua answers from a built-in list of questions and answers.

**Keeping Pua up to date:** when something on the site changes, update the `FACTS` and `LOCAL_ANSWERS` lists at the top of `js/pua.js` so her answers stay correct.

## How the files are organized

```
index.html, *.html   one file per page
css/site.css         colors, fonts and layout shared by every page
js/pua.js            Pua the helper and the music button
images/              bracelet photos and the Beadiful Chaos logo
```

- **Colors and fonts** are set once at the top of `css/site.css`, so you can change the whole site's look in one place.
- **New pages** can copy an existing page as a starting point. Add a surfboard link to the new page on the home page.

## Viewing the site

- **Online:** publish it with GitHub Pages (Settings → Pages → deploy from the `main` branch, `/ (root)` folder). After that, changes pushed to `main` usually show up within a few minutes.
- **On your computer:** download the repo and double-click `index.html` to open it in a browser. No installation needed.

## Still to do

- [ ] Add the bracelet order form (a Google Form made with a grown-up's account)
- [ ] Fill in favorite gymnastics events, choir songs and video titles

## Privacy rules for this site

This is a kid's website, and it's public. Before adding anything, check that it does **not** include:

- Lulu's last name, school, town, address, phone number or personal email
- Photos that show her face, school, home or anything with a location
- Exact dates and places of performances or meets

Orders and emails go through a grown-up's account, never Lulu's own.
