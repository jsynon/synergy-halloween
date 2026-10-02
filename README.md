# Halloween Fashion Spectacular

A single-page digital flyer for the **Wanted Alliance Costume Contest**, presented by Synergy. Built for the Neverwinter community, it works as a shareable link with a live countdown to the finale.

**Live page:** _add your hosted URL here_

## Event details

- **Event:** Halloween Fashion Spectacular (Wanted Alliance Costume Contest)
- **Prizes:** 50 Million Astral Diamonds split between 5 winners, plus the "Frightfully Fashionable" title
- **Sign-ups close:** October 10th
- **Qualifying round:** October 17th, 8:00 PM Eastern, at each guild Stronghold
- **Live finale:** Saturday, October 24th, 8:00 PM Eastern
- **Watch live:** [twitch.tv/thenolanian](https://www.twitch.tv/thenolanian)
- **Hosts:** Nolanian & Ivydora

## Features

- Countdown timer to the live finale, with "live now" and "ended" states
- Finale time shown in the visitor's own time zone
- "Add to Google Calendar" button
- Sign-up line that shows days remaining, then switches to "closed"
- Timeline steps that dim automatically once they've passed
- Responsive layout for phones and desktops
- Original flyer included at the bottom of the page

## Files

| File | Description |
| --- | --- |
| `index.html` | The entire site: HTML, CSS, JavaScript and embedded images |

The page is fully self-contained. The only external resource is Google Fonts, and the page falls back to Georgia if the fonts don't load.

> If your file is named `halloween-fashion-spectacular.html`, rename it to `index.html` so GitHub Pages serves it at the root URL.

## Hosting on GitHub Pages

1. Push `index.html` to your repository.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select your main branch and the `/ (root)` folder, then save.
5. After a minute or two, your site will be live at `https://<your-username>.github.io/<repo-name>/`.

You can also upload the file to any static host, such as TinyHost, Netlify or Cloudflare Pages.

## Customizing

Open `index.html` in a text editor.

- **Event date and time:** find the `target` line near the bottom of the `<script>` block. Dates use ISO format with the Eastern offset (`-04:00` during daylight time, `-05:00` after November 1st).
- **Sign-up deadline:** edit the `signupClose` line in the same script.
- **Text and links:** edit the HTML directly. Search for the text you want to change.
- **Colors:** the palette is defined as CSS variables at the top of the `<style>` block (`--gold`, `--pumpkin`, `--night`, and so on).

## Link previews (optional)

To get a preview card when you share the link in Discord or social media, add these tags inside `<head>` once you know your hosted URL:

```html
<meta property="og:title" content="Halloween Fashion Spectacular">
<meta property="og:description" content="Wanted Alliance Costume Contest. 50 Million Astral Diamonds and the Frightfully Fashionable title. Live on Twitch October 24th at 8:00 PM Eastern.">
<meta property="og:image" content="https://your-site-url/flyer.jpg">
<meta property="og:type" content="website">
```

The image must be a separate file hosted at a public URL, so save the flyer as `flyer.jpg` in your repository and point to it.

## Credits

Event presented by Synergy and hosted by Nolanian & Ivydora. Neverwinter and its artwork are trademarks of their respective owners. This is a fan-run community event and is not affiliated with or endorsed by them.
