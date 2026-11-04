# Need Blindness Cheat Sheet

An interactive decision tree for when you can't tell what your body actually needs. Hungry? Tired? Overstimulated? Just bored? Answer a few questions, get a hack that might help.

🔗 **Live:** https://needblindness.faystack.com

![Need-Blindness-SS](need-blindess.png)

## What it does
- Walks you through a quick decision tree to narrow down what you need
- 34 practical hacks across five categories
- Community suggestion form so people can submit their own hacks

## Why I built it
Started as a TikTok idea. Lots of people said they struggle to tell the difference between hunger, thirst, tiredness and overwhelm, so I turned it into something you can actually click through.

## Built with 
HTML · CSS · JavaScript · Google Apps Script · Google Sheets · Vercel
And Claude

## How it works
The site is a single static page hosted on Vercel. Suggestions are sent to a Google Apps Script endpoint, which writes each one as a new row in a Google Sheet. No database, no server, no cost.

## What I learned
- Connecting a static site to Google Sheets without a backend
- Deploying with Vercel and custom subdomains
- Designing a decision tree that feels quick, not like a quiz

---
Part of [faystack](https://faystack.com). 
