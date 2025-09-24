# Hero image guidance

Suggested approach: use an AI-generated, abstract-yet-professional background that suggests technology + legal context without using any logos or sensitive content.

File path to use: `assets/hero/hero-ai.jpg`
Then add `with-image` to the hero section class in `web/index.html` to enable the background overlay.

1) Visual direction
- Abstract, clean, premium feel (no literal “robots” or cliché gavels).
- Subtle shapes/lines hinting data flows, documents, and network graphs.
- Color palette aligned with Orbital: deep charcoal (#0B0B0D), red accents (#E11D2E / #FF334E), soft neutrals.
- High contrast with soft gradients; avoid busy textures that compete with text.

2) Prompt starter (Midjourney/Stable Diffusion)
"minimalist futuristic abstract background, subtle data flow lines, soft gradients in deep charcoal and crimson accents, premium corporate feel, high contrast, negative space, no text, no logos, cinematic lighting, bokeh, depth of field, 16:9, ultra-detailed, clean UI aesthetic"

Negative prompt: "humans, faces, scales of justice, hammers, robots, clutter, watermark, text"

3) Composition tips
- Keep the brightest area behind the left/top area of the hero text.
- Use blur and low-frequency detail; text legibility is top priority.
- Export at least 1920×1080 (ideally 2400×1350) JPG optimized (75–85 quality).

4) How to enable it
- Save the final image as `assets/hero/hero-ai.jpg`.
- In `web/index.html`, change `<section class="hero" id="hero">` to `<section class="hero with-image" id="hero">`.
- Verify contrast on desktop and mobile.

5) Licensing
- Ensure the generated image is license-free for commercial use and free of third-party marks.

6) Alt text
- Since this is decorative, keep it as CSS background only and avoid extra `<img>`; accessible name comes from hero heading.
