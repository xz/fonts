# xz/fonts

**A fast, open-source CDN for open-source fonts.**

xz/fonts is a free and open source service for delivering font families to websites using CSS. 

Typically, web developers use custom fonts on their websites using one of two methods:
- hosting font files on the same server as the website
- using a central font service, such as Google Fonts or Adobe Typekit

xz/fonts, by comparison:
- serves font files through jsDelivr's global content delivery network
- is fully open source and only serves open source fonts

---

For the font Inter, it's as easy as adding this to your CSS:

```css
@import url('https://cdn.jsdelivr.net/npm/@xz/fonts@1/serve/inter.css');
```

or this to your HTML's `<head>`:

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@xz/fonts@1/serve/inter.css">
```

## Usage

Visit the documentation at [docs.xz.style/fonts](https://docs.xz.style/fonts) for an easy step-by-step guide. 

## Having trouble?

Don't worry! [Open an issue here](https://github.com/xz/fonts/issues). I'll gladly help you out.

## Special Thanks

❤️ to [transfonter.org](https://transfonter.org/) for providing a fast and reliable service for converting `.ttf` font files to multiple web formats. If you love what they do, consider [donating](https://transfonter.org/donate) to them! I'm not affiliated in any way, just love the service.

***
<a href="https://vercel.com" target="_blank">![Powered by Vercel](https://vercel-badges.now.sh/powered-by-vercel.svg)</a>
