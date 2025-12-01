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

## Contributing

If you found other characters that Priority eats, feel free to submit a PR. Let's build a database of Priority's password crimes together 💀

## License

Do whatever you want with this. If it saves you from Priority's password shenanigans, that's payment enough.

---

*Made by someone who's tired of Priority's nonsense*
