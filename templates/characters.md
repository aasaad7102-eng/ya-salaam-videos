# Character rule (all future videos)
- Each character = its own pose sheet image (never several characters in one image).
- 8 poses per character, chosen from that video's scenes, full body, large gaps, nothing touching/cropped.
- Transparent background (fallback: flat pure green #00FF00). Landscape 16:9, highest resolution.
- Style: glossy 3D CGI family-movie look (kids-3d-scenes style). Same outfit/face in every pose.
- The user generates the images from the prompts Claude writes and brings them back; Claude cuts each pose and animates.
- Backgrounds: separate vertical 9:16 high-res prompts.

# Layering rule (scene staging) — always
- Never let two characters overlap or "enter into" each other in a shot: keep a clear gap between bodies.
- Depth order by feet position: the character whose feet are lower on screen is in front (higher z); back row smaller and higher, front row bigger and lower.
- Tags, captions and pops sit above all characters; props held by a character stay on that character's layer.
- When a character steps forward (spotlight), others shift aside so nobody covers anyone.
