# Your portfolio 🎬

Happy birthday, Anand. This site is yours now. Here's how to make it your own.

## Edit everything in one place
Open `index.html` and find the block marked **EDIT EVERYTHING HERE ✏️** near the top of the `<script>`.
Every bit of text, every link and every number on the page comes from that `CONFIG` object:

| What | Where in CONFIG |
|---|---|
| Name, roles, tagline | `name`, `fullName`, `roles`, `tagline` |
| Showreel link | `showreel.url` |
| Your edits and projects | `works`: `cat` is `"film"` or `"tech"`, `url` is a YouTube/Insta/GitHub link |
| Locked "CLASSIFIED" cards | delete `locked: true` from a work and fill in its details |
| Skills timeline | `tracks` |
| Box office numbers | `stats` |
| Scrolling marquee | `marquee` |
| Socials and email | `socials`, `email` |

## Images
Put photos in a `photos/` folder next to `index.html` and reference them as `"photos/name.jpg"`.

## The birthday surprise
It's the "post-credits scene" after THE END. To remove it later, set `birthday.enabled: false`.
To open the site straight into the surprise, add `#surprise` to the end of the link.

## Put it online (free)
- **Vercel / Netlify:** drag the folder in. Done.
- **GitHub Pages:** push the folder to a repo, then Settings → Pages → deploy from `main`.

All sounds are generated in the browser, so there are no audio files to manage.
