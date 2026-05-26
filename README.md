# Book Factory — AI Children's Book Maker for Amazon KDP

> **Write, illustrate, and self-publish a full children's book in minutes — powered by Google Gemini.**

Book Factory is a free desktop app that turns a single sentence into a finished, KDP-ready picture book: an original story, custom AI illustrations on every page, a cover, and exportable PDF + metadata for Amazon Kindle Direct Publishing.

> **No subscriptions. No watermarks. No artists needed.** You bring an idea — Book Factory writes the story, draws every page, and gives you everything you need to upload to Amazon KDP and start earning royalties.

[![Download for macOS (Apple Silicon)](https://img.shields.io/badge/Download-macOS%20Apple%20Silicon-orange?style=for-the-badge&logo=apple)](../../releases/latest)
[![Download for macOS (Intel)](https://img.shields.io/badge/Download-macOS%20Intel-blue?style=for-the-badge&logo=apple)](../../releases/latest)

[👉 Get the latest release](../../releases/latest)

---

## Why creators love Book Factory

- **AI that actually understands kids' books.** Built on Google's Gemini models with prompt engineering tuned specifically for early-reader, picture book, and bedtime-story formats — not a generic chatbot bolted onto a stable diffusion model.
- **Consistent characters across every page.** Your protagonist looks like the same character on page 1 and page 28 — solved.
- **One-click Amazon KDP export.** Print-ready interior PDF + cover + metadata.json sized to KDP specs. Skip the InDesign rabbit hole.
- **You own everything.** Stories are saved as plain folders on your computer — no cloud lock-in, no DRM, your books are yours.
- **Bring your own Gemini key.** Pay Google's pennies-per-book API rate directly. No middleman markup, no monthly subscription.
- **Native desktop app.** Runs offline-first (once Gemini returns the assets). No "log in to keep working" nonsense.

## What you can make

- 📖 **Picture books** for ages 2–6
- 📚 **Early reader books** for ages 5–8
- 🌙 **Bedtime story collections**
- 🎨 **Coloring books** with consistent line-art characters
- 🦄 **Series books** featuring the same recurring characters
- 🎄 **Holiday & gift books** personalized for family members

## How it works (3 steps, ~10 minutes per book)

1. **Describe your idea.** "A shy dragon who's afraid of the dark learns to make friends with the moon."
2. **Review the story.** Book Factory writes a full, age-appropriate picture book with chapters/pages laid out for you. Edit any line you want.
3. **Generate the illustrations.** Hit go — Book Factory uses Gemini's image model to draw every page in your chosen art style, then bundles everything into a print-ready PDF + KDP metadata file.

## Download

The latest release is always at **[releases/latest](../../releases/latest)**. Pick the right file for your Mac:

| Your Mac | Download |
|---|---|
| **Apple Silicon** (M1, M2, M3, M4) | `BookFactory-<version>-arm64.dmg` |
| **Intel** (2015–2020 Macs) | `BookFactory-<version>-x64.dmg` |

Not sure which one? Click the Apple menu → **About This Mac**. If it says "Apple M1/M2/M3/M4" pick arm64, otherwise pick x64.

### Install

1. Double-click the downloaded `.dmg`
2. Drag **Book Factory** into your Applications folder
3. Launch from Launchpad

Every release is **signed and notarized by Apple**, so macOS will let you open it without security warnings or right-click workarounds.

## Setup (one time, ~2 minutes)

You'll need a **free** Gemini API key from Google AI Studio — Google gives you a generous free tier that's enough for plenty of books.

1. Open [aistudio.google.com](https://aistudio.google.com) and sign in with a Google account
2. Click **Get API key** → **Create API key**
3. Copy the key (starts with `AIza...`)
4. Paste it into Book Factory on first launch — done

Your key is stored only on your computer. It's never sent anywhere except directly to Google when generating a book. You can change it anytime in **Settings**.

## Frequently asked questions

### Is Book Factory free?
The app is free. You pay Google directly for the AI calls — typically **a few cents per page** at current Gemini pricing. A full 30-page illustrated children's book usually costs **under $1** in API calls.

### Can I sell the books I make on Amazon KDP?
Yes. The books you generate are yours to publish, sell, and keep 100% of the royalties on. Book Factory exports a print-ready interior PDF and metadata file sized exactly to Amazon KDP specs.

### Do I need any design or writing skill?
No. If you can describe a book in one sentence, Book Factory can build it. You can always edit the story before generating illustrations.

### Do the illustrations look consistent across the book?
Yes — that's the hardest part of using AI for kids' books, and it's the problem Book Factory was built to solve. Your characters look like the same characters on every page.

### Will there be a Windows version?
Yes — Windows builds are on the roadmap. ⭐ Star this repo to be notified when it ships.

### Does it work offline?
You need internet for the AI generation step (Gemini lives in Google's cloud). Once a book is generated, all editing, previewing, and PDF export work fully offline.

### Where are my books saved?
Right next to the Book Factory app, in a `books/` folder — plain folders with your images and a `project.json`. No proprietary format, no cloud lock-in.

### What models does it use?
Currently Gemini 3 Flash for story reasoning and Gemini's image generation model for the illustrations. The app updates automatically as Google ships better models.

## Roadmap

- ✅ macOS app (signed + notarized) — **shipping now**
- 🔜 Windows app
- 🔜 Cover designer with AI typography
- 🔜 Multi-language books (Spanish, French, Mandarin, Arabic)
- 🔜 Audio narration export for Audible Children's Books
- 🔜 EPUB export for Kindle e-books

## Support

- 🐛 Found a bug? Open an issue on this repo.
- 💡 Feature request? Open an issue with the `enhancement` label.
- ⭐ Like the app? Star this repo — it helps other creators find Book Factory.

---

**Keywords:** AI children's book generator, AI book maker, Amazon KDP children's books, self-publish children's book AI, Gemini AI book creator, AI picture book generator, free children's book maker for Mac, AI illustrated book maker, kid's book writing software, AI bedtime story generator, Amazon KDP self-publishing tool, AI book illustrator, AI storybook maker, Apple Silicon book creator app, AI children's book illustrations.
