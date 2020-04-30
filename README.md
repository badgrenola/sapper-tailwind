# Sapper + TailwindCSS = 👍

This repo is my [Sapper](https://sapper.svelte.dev/) and [TailwindCSS](https://tailwindcss.com/) boilerplate.

## Package Scripts

### Long story short 
* For development : `npm run dev`
* For building your static app bundle : `npm run export`

### Hot Reloading
After trying a few suggested Tailwind/Sapper setups, I found that running two processes (one that watches for Tailwind updates, and one that builds Sapper) gave me the quickest hot-reload results.