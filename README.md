# tailwind-login

I made this clone of the DigitalOcean login screen to demonstrate the capabilities
of Tailwind CSS. Prior to this, I had zero experience Tailwind CSS, but it only
took me about 1.5 hours to complete. Much of the time was spent looking up class
names and learning how Tailwind works, and by the end I had already memorized
some patterns and was able to quickly make specific styles—all without
writing a single line of CSS!

A few benefits I noticed:

- No need to switch between HTML and CSS files
- There are enough composeable utilities so that almost any design can be created
- The ability to extract components ensures no duplicate code
- No need to come up with class names (except when extracting components)
- You can tell what the page looks like by looking at the HTML
- Does not suffer from looking like every other website made with Tailwind
  because the utilities are so small

And a few drawbacks:

- Some setup required in the build system when using it in production
- Very specific designs may be difficult to create
- No support for animations
- Slower for making quick prototypes

Run this to generate the CSS file:
```
npx tailwind build style.css -o output.css -c tailwind.config.js
```

**Warning**: The above command is for demonstration purposes only. It does not
remove unused styles, so the file is much larger than it should be. Don't use
this for a production build. Read [Controlling File Size](https://tailwindcss.com/docs/controlling-file-size) if you plan to use Tailwind in production.

## License

Unlicense
