---
layout: layouts/base.njk
title: "About"
permalink: /about/
eleventyExcludeFromCollections: true
---

<h1 id="about"><a href="#about">About</a></h1>

<div class="about-hero-text">
  <span class="about-kicker">{{ site.name }} · TECHNICAL NOTEBOOK</span>
  <p class="about-intro">Replace this intro in `src/about.md` with your own bio. Eleventy Silicon is built for engineers, developers, and makers who want a fast, distraction-free personal notebook.</p>
</div>

> "Everything proceeds mathematically... if someone could have a sufficient insight into the inner parts of things, he would be a prophet and would see the future in the present as in a mirror."
>
> &mdash; **Gottfried Wilhelm Leibniz**

## What this site is

This website is basically my own technical notebook, made public. It's where I document projects, experiments, fixes, and the occasional problem that took far longer to solve than it should have. Some articles might be useful to someone else, and at the very least I'll have somewhere to find the solution when I inevitably need it again.

I don't pretend to know everything. I'm still learning, experimenting, and breaking things along the way. If something here is useful to you, great. If you've spotted a mistake or have a better way of doing something, even better — feel free to get in touch on the [contact page](/contact/).

All opinions here are my own. Thanks for stopping by.

<div class="about-chip-signoff" aria-hidden="true">
  <svg class="about-chip" viewBox="0 0 160 120" fill="none" stroke="currentColor" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round">
    <!-- PCB traces -->
    <path d="M8 28h18M8 44h18M8 60h18M8 76h18M8 92h18" stroke="var(--border)" stroke-width="1.4"/>
    <path d="M134 28h18M134 44h18M134 60h18M134 76h18M134 92h18" stroke="var(--border)" stroke-width="1.4"/>
    <circle cx="8" cy="28" r="2.2" fill="var(--accent)" stroke="none"/>
    <circle cx="8" cy="60" r="2.2" fill="var(--accent)" stroke="none"/>
    <circle cx="8" cy="92" r="2.2" fill="var(--accent)" stroke="none"/>
    <circle cx="152" cy="44" r="2.2" fill="var(--accent)" stroke="none"/>
    <circle cx="152" cy="76" r="2.2" fill="var(--accent)" stroke="none"/>
    <!-- DIP Pins Left -->
    <line x1="26" y1="28" x2="38" y2="28" stroke="var(--accent)"/>
    <line x1="26" y1="44" x2="38" y2="44"/>
    <line x1="26" y1="60" x2="38" y2="60" stroke="var(--accent)"/>
    <line x1="26" y1="76" x2="38" y2="76"/>
    <line x1="26" y1="92" x2="38" y2="92" stroke="var(--accent)"/>
    <!-- DIP Pins Right -->
    <line x1="122" y1="28" x2="134" y2="28"/>
    <line x1="122" y1="44" x2="134" y2="44" stroke="var(--accent)"/>
    <line x1="122" y1="60" x2="134" y2="60"/>
    <line x1="122" y1="76" x2="134" y2="76" stroke="var(--accent)"/>
    <line x1="122" y1="92" x2="134" y2="92"/>
    <!-- DIP IC Package -->
    <rect x="38" y="14" width="84" height="92" rx="6" fill="var(--bg)" stroke="var(--accent)" stroke-width="2"/>
    <rect x="44" y="20" width="72" height="80" rx="3" fill="var(--accent-faint)" stroke="var(--accent-border)" stroke-width="1"/>
    <!-- IC Notch & Pin-1 Dot -->
    <path d="M72 14a8 8 0 0 0 16 0" fill="var(--bg)" stroke="var(--accent)" stroke-width="2"/>
    <circle cx="51" cy="27" r="2" fill="var(--accent)" stroke="none"/>
    <!-- Silkscreen Typography -->
    <text x="80" y="57" text-anchor="middle" fill="var(--text)" stroke="none" font-family="Roboto Mono, monospace" font-weight="700" font-size="14" letter-spacing="1.5">{{ site.chipTitle }}</text>
    <line x1="56" y1="66" x2="104" y2="66" stroke="var(--accent-border)" stroke-width="1"/>
    <text x="80" y="79" text-anchor="middle" fill="var(--accent)" stroke="none" font-family="Roboto Mono, monospace" font-weight="500" font-size="7.5" letter-spacing="1">{{ site.chipRev }}</text>
    <text x="80" y="91" text-anchor="middle" fill="var(--muted)" stroke="none" font-family="Roboto Mono, monospace" font-size="6.5" letter-spacing="0.8">{{ site.chipSub }}</text>
  </svg>
</div>
