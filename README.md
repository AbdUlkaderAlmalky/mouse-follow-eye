<p align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=220&text=Mouse%20Follow%20Eyes&fontSize=44&color=0:0073ff,100:66d4ff&fontColor=ffffff" alt="Mouse Follow Eyes banner" />
</p>

# Mouse Follow Eye

A playful JavaScript interaction where a pair of CSS-drawn eyes rotate to follow the user's mouse cursor.

## Project Concept

The project uses mouse coordinates and element positions to calculate an angle for each eye. JavaScript then rotates the eyes dynamically, creating the illusion that they are watching the cursor move across the page.

## How It Works

1. Listen for the browser's `mousemove` event.
2. Find the center point of each eye.
3. Calculate the cursor angle with `Math.atan2()`.
4. Convert the angle to degrees.
5. Apply a CSS rotation transform.

## Tech Stack

- HTML5
- CSS3
- Vanilla JavaScript
- DOM Events
- `Math.atan2()`

## Run Locally

```bash
git clone https://github.com/AbdUlkaderAlmalky/mouse-follow-eye.git
cd mouse-follow-eye
```

Open:

```text
eye/index.html
```

## Purpose

A compact frontend experiment demonstrating coordinate geometry, mouse events, DOM measurements, and CSS transforms.
