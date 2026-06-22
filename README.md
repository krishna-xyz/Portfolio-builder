# Portfolio Builder

A simple browser-based tool to create your own portfolio page — pick a preset, fill in your details, and download your ready-to-deploy HTML file. No frameworks, no build step, just open `index.html` and go.

**Live demo:** [https://portfolio-builder-krishna.netlify.app](https://portfolio-builder-krishna.netlify.app)

---

## Presets

| Theme | Best for |
|---|---|
| Developer | Programmers, engineers, open source folks |
| Artist | Designers, illustrators, photographers |
| Writer | Authors, bloggers, journalists |
| General | Anyone who doesn't fit a box |

---

## Getting started locally

Just clone and open — no install needed.

```bash
git clone https://github.com/krishna-xyz/portfolio-builder.git
cd portfolio-builder
# open index.html in your browser
```

Or grab the zip from GitHub and extract it.

---

## Deploy to Netlify (via GitHub)

This is the easiest way to get a live URL for free.

### Step 1 — Fork the repo

Click **Fork** on the top-right of this page. This creates your own copy under your GitHub account.

### Step 2 — Connect Netlify

1. Go to [netlify.com](https://netlify.com) and sign up / log in with your GitHub account
2. Click **Add new site → Import an existing project**
3. Choose **GitHub** and authorize Netlify
4. Find and select your forked repo

### Step 3 — Configure build settings

Netlify should auto-detect the settings. If it asks:

- **Build command:** *(leave empty)*
- **Publish directory:** `.` (a single dot)

Click **Deploy site**.

### Step 4 — Done

Netlify gives you a URL like `https://your-name-abc123.netlify.app`. You can rename it under **Site settings → Domain management**.

---

## How to use the builder

1. Open the site
2. Pick a preset from the top (Developer, Artist, Writer, General)
3. Fill in your name, tagline, age, bio, and social links
4. Add your skills or portfolio links in the cards section
5. Pick a color accent you like
6. Hit **Download Portfolio** — you get a single `portfolio.html` file
7. Drop that file anywhere: Netlify drop, GitHub Pages, your own server

---

## Project structure

```
portfolio-builder/
├── index.html        # the whole app lives here
├── LICENSE
└── README.md
```

Everything is in one file on purpose — makes it trivially easy to host anywhere that serves static files.

---

## Contributing

Issues and PRs welcome. Keep it simple — the goal is zero dependencies.

---

## Credits

Built by [krishna-xyz](https://github.com/krishna-xyz)

---

*MIT License — free to use, modify, and share.*
