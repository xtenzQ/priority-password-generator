# Priority Password Generator 🔐

## Why does this exist?

So basically Priority (that project tracking software everyone's company uses for some reason) has this super weird bug where you change your password and then boom - it doesn't work anymore. Like you literally just typed it, confirmed it twice, and Priority goes "nah who dis?" when you try to login.

I'm pretty sure it's got something to do with special characters getting escaped or stored in some cursed way that doesn't match what you actually typed. Priority's password handling is coded like it's still 1999 or something lmao.

## The Solution

This app generates passwords using ONLY characters that Priority won't have a mental breakdown over:

- Letters: `a-z` and `A-Z`
- Numbers: `0-9`
- Symbol: `!` (just the exclamation mark, nothing fancy)

No `@`, no `#`, no `$` - none of that stuff Priority apparently can't handle properly. Just good old safe characters that won't get mangled by whatever ancient password storage system they're using.

## Features

- **Auto-generates** a 16-character password when you load the page
- **Copy button** - one click and you're good to go
- **Regenerate button** - don't like the password? Get a new one
- **Actually works with Priority** - tested and doesn't get eaten by their system
- **Clean UI** - Apple-like design cause we ain't savages

## How to use

1. Open `index.html` in your browser
2. Copy the password (click the copy icon)
3. Change your Priority password to this one
4. Actually be able to login afterwards (revolutionary concept, I know)

## Technical stuff

- Built with Vue 3
- No build step needed, just open the HTML file
- Password length: 16 characters (secure enough without being annoying)
- Guarantees at least 1 lowercase, 1 uppercase, 1 number, and 1 ! symbol

## Why 16 characters?

Cybersecurity folks say 12-16 chars is the sweet spot for password strength. More than that and you're just making your life harder for marginal security gains. 16 is long enough to be secure but not so long you'll rage quit typing it.

## Deploy

Literally just host the `index.html` file anywhere. GitHub Pages, Netlify, your company's internal server, whatever. It's just one HTML file with everything included.

Or just open it locally, works the same lol.

## Contributing

If you found other characters that Priority eats, feel free to submit a PR. Let's build a database of Priority's password crimes together 💀

## License

Do whatever you want with this. If it saves you from Priority's password shenanigans, that's payment enough.

---

*Made by someone who's tired of Priority's nonsense*
