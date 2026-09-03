# AppADay 118 — Divine Mercy Chaplet Companion

Part of [AppADay](https://augustineiacopelli.github.io/appaday/), a daily discipline project by Augustine Iacopelli: one complete, functional, mobile-friendly web app shipped every single day.

## What it does

A calm, guided companion for praying the Chaplet of Divine Mercy. Tap through all 64 steps in order: the sign of the cross, the opening Our Father, Hail Mary, and Apostles' Creed, five decades each carrying the offering prayer and its ten petitions, the triple Holy God, the closing prayer, and a final sign of the cross. A progress line and bar track where you are in the chaplet at every step.

## How it works

Everything lives in one self-contained `index.html` with no external dependencies and no network calls, so the chaplet can be prayed fully offline. The current step is held in a single index variable, mirrored to `localStorage` so a closed tab picks back up where it left off. Tapping the prayer card or the Next button advances the sequence, clamping at the final step rather than wrapping around; reaching the end changes the button to "Begin Again." Reset returns to the first step at any time.

## Category

Spirituality (S). No AI features, no external calls, fully offline-capable.

## Live app

https://augustineiacopelli.github.io/appaday-118-divine-mercy-chaplet/
