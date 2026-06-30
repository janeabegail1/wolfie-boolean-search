# 🐺 Wolfie — X-Ray Talent Search

A powerful, single-page boolean search builder that generates Google X-ray search strings to surface candidates from:

- 💼 **LinkedIn** — profiles (`site:linkedin.com/in/`)
- 🐙 **GitHub** — user pages & repositories (`site:github.com`)
- 📚 **Stack Overflow** — user profiles (`site:stackoverflow.com/users/`)
- 🎓 **Google Scholar** — author citation pages (`site:scholar.google.com/citations`)

## What is X-Ray Search?

X-ray search uses Google's `site:` operator to search *inside* a platform without logging in. It surfaces publicly indexed profiles that standard recruiter searches miss.

## Features

- ✅ Select target platforms (toggle on/off)
- ✅ Enter job title / role (searched as exact phrase)
- ✅ Click-to-select skills from a curated list (35+ skills)
- ✅ OR / AND join mode for skills
- ✅ Add custom keywords with OR / AND / NOT operators
- ✅ Location targeting
- ✅ Noise filter — exclude recruiters, job posts, students, etc.
- ✅ Syntax-highlighted query preview
- ✅ One-click open in Google for each platform
- ✅ Copy individual query strings
- ✅ Open all platforms in new tabs at once
- ✅ Dark mode UI

## Deploy on Vercel

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/janeabegail1/wolfie-boolean-search)

1. Fork or import this repo into Vercel
2. No build step required — it's pure HTML/CSS/JS
3. Vercel auto-deploys on every push to `main`

## Tech Stack

Pure HTML + CSS + vanilla JavaScript. Zero dependencies, zero build tools. Drop-in deploy anywhere.
