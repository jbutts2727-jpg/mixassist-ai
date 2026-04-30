# MixAssist AI

MixAssist AI is a self-contained local web app for live sound teams. It helps church teams, small venues, and front-of-house volunteers quickly build a practical mix plan or troubleshoot common live audio problems.

The app was created as a demo project for the Handshake Codex Creator Challenge.

## What It Does

MixAssist AI has two main workflows:

- **Build My Mix**: Creates a practical live sound starting plan from a band or input setup.
- **Fix My Mix**: Generates a troubleshooting plan for problems like muddy vocals, feedback, weak livestream audio, harsh guitars, and monitor issues.

The app can generate demo-ready output with:

- Organized channel layouts
- Gain staging targets
- EQ starting points
- Compression suggestions
- Mix priorities
- Console-specific tips
- Fast demo presets
- Copyable AI prompts and output

## How To Run It

No install step is required.

1. Open the project folder.
2. Open `index.html` in any modern browser.
3. Choose **Build My Mix** or **Fix My Mix**.
4. Adjust the setup, console, room type, or experience level.
5. Click **Generate demo output**.

Because everything is contained in `index.html`, the app works without a dev server, package manager, build tool, or internet connection.

## Files

- `index.html`: The full MixAssist AI app, including HTML, CSS, and JavaScript.
- `README.md`: Project overview and challenge notes.

## How I Used Codex

I started with a React component idea for MixAssist AI: a tool with two modes, **Build My Mix** and **Fix My Mix**, aimed at helping live sound volunteers. Since the project folder did not already contain a React app, I asked Codex to turn the idea into a self-contained local web app that would be easy to demo.

Codex helped by:

- Converting the original React concept into a standalone `index.html` app.
- Designing a polished interface with responsive layout, mode cards, a hero section, controls, and output panel.
- Adding realistic demo presets for Sunday bands, conference panels, vocal feedback, and livestream mix problems.
- Writing the client-side JavaScript for switching modes, generating demo output, and copying prompts or results.
- Keeping the app dependency-free so it can be opened directly in a browser during the challenge demo.
- Validating the embedded JavaScript syntax to reduce the chance of demo-day breakage.

The result is a working prototype that communicates the product idea quickly: MixAssist AI gives practical live sound guidance in seconds for teams that may not have a trained audio engineer available.

## Challenge Pitch

MixAssist AI helps church teams and small venues build a better live mix or troubleshoot sound problems in seconds, even without years of audio training.

## 3-Minute Demo Script

**0:00-0:30 — Introduce the problem**

"This is MixAssist AI, a live sound assistant for church teams, small venues, and volunteer audio techs. The problem I wanted to solve is simple: a lot of teams are responsible for live sound, but they do not always have a trained front-of-house engineer in the room. When something sounds muddy, feeds back, or feels unbalanced, they need practical help fast."

**0:30-1:15 — Show Build My Mix**

"The first mode is Build My Mix. I can enter a band setup, choose the console, choose the room type, and set the experience level. For example, here is a typical Sunday band with drums, bass, guitars, keys, tracks, vocals, and choir. When I click Generate demo output, MixAssist creates a usable starting plan with a channel layout, gain staging targets, EQ starting points, compression suggestions, and mix priorities."

**1:15-2:00 — Show Fix My Mix**

"The second mode is Fix My Mix. This is for the moment when something is already going wrong. I can choose the vocal feedback preset or type a problem like, 'Lead vocal sounds muddy and starts feeding back when the singer gets loud.' The app generates likely causes, step-by-step fixes, specific EQ and compression moves, monitor checks, and what to check first during a service or event."

**2:00-2:35 — Explain the Codex build**

"I built this with Codex for the Handshake Codex Creator Challenge. I started with a React component idea, then used Codex to turn it into a polished, self-contained local web app. Codex helped design the interface, write the HTML, CSS, and JavaScript, add realistic demo presets, and make it dependency-free so it opens directly in the browser."

**2:35-3:00 — Close with the value**

"The goal is not to replace an experienced engineer. The goal is to give smaller teams a calm, practical assistant that helps them make better decisions under pressure. MixAssist AI turns audio knowledge into clear next steps that a volunteer can actually use."
