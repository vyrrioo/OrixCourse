# OrixCourse — YouTube Automation Mastery

A premium course landing page for YouTube Automation, ready to deploy on GitHub Pages in one click.

## 🚀 Deploy on GitHub Pages (Free Hosting)

1. **Fork or upload** this repo to your GitHub account
2. Go to **Settings → Pages**
3. Under "Source", select `main` branch → `/ (root)`
4. Click **Save**
5. Your site will be live at `https://yourusername.github.io/orixcourse`

That's it — no server, no cost, no code needed.

---

## 📁 File Structure

```
orixcourse/
├── index.html       ← The full course landing page
├── README.md        ← This file
└── .nojekyll        ← Tells GitHub Pages to skip Jekyll processing
```

## ✏️ How to Customize

Open `index.html` in any text editor and change:

| What | Where to find it |
|------|-----------------|
| Your name | Search `Alex Orix` |
| Prices | Search `$97`, `$197`, `$397` |
| Stats (subs, revenue) | Search `$240,000` |
| Payment links | Search `href="#"` on the enroll buttons |
| Testimonials | Search `testi-card` |
| Course title | Search `OrixCourse` |

## 💳 Adding Real Payment Links

Replace the `href="#"` on each pricing button with:
- **Gumroad**: `https://yourname.gumroad.com/l/product-name`
- **Stripe**: Your Stripe payment link
- **ThriveCart / Kajabi**: Your checkout URL

## 🎨 Colors

Edit the CSS variables at the top of `index.html`:
```css
:root {
  --red: #FF2D2D;    /* Main accent */
  --gold: #FFB800;   /* Secondary accent */
  --dark: #0A0A0A;   /* Background */
}
```

## 📱 Mobile Responsive

Fully responsive. Tested on mobile, tablet, and desktop.

---

Built with pure HTML, CSS & vanilla JS — zero dependencies, zero frameworks. Loads in under 1 second.
