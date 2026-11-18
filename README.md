# Μιλάω • I Can Say It

A responsive, bilingual Greek/English AAC (augmentative and alternative communication) web app. Designed for children who communicate by selecting words and building sentences.

## Features
- Greek and English interface and vocabulary
- Picture-based communication tiles and category filters
- Sentence strip: tap words to add them; tap a sentence chip to remove it
- Native browser text-to-speech using Greek (`el-GR`) and English (`en-US`) voices
- Add a custom word for the current session
- Responsive portrait and landscape layouts for phones, tablets and desktops
- No account, database, analytics, API keys, or saved history

## Run locally
Open `index.html` in a browser, or serve this folder with any static file server.

## Deploy to Vercel
Import this GitHub repository into Vercel. It is a static site; no build command, install command, environment variables, or database are required. Vercel will serve `index.html` from the project root.

## Speech support
Speech uses the browser's built-in Web Speech API. Voice availability depends on the operating system, browser, installed voices and device settings. On iOS/iPadOS, speech may require a user tap and the device's speech voices to be enabled. The app does not send text to a third-party service.

## Accessibility note
This is a communication aid, not a replacement for an individualized AAC assessment or speech-language therapy. Keep important words available and customize vocabulary to the child's everyday communication needs.
