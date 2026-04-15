# HOW TO USE THESE FILES WITH CLAUDE CODE
# Read this first before starting

---

## FILES TO UPLOAD TO CLAUDE CODE (in this order):

1. teodora-knowledge-base-v3.md
   → All content about you, your career, your metrics,
     your story. Claude Code reads this for all the copy.

2. teodora-website-claude-code-prompt.md
   → The full build brief. Paste this as your first message
     OR upload it and say "Build the website described in
     this file using the knowledge base I also uploaded."

---

## WHAT TO SAY TO START:

Option A (paste prompt directly):
Copy the entire contents of the prompt file and paste it
as your first message in Claude Code.

Option B (upload files):
Upload both files, then say:
"Build me the personal website described in
teodora-website-claude-code-prompt.md
using all the content from teodora-knowledge-base-v3.md.
Start with the HTML and CSS, then we'll refine."

---

## AESTHETIC INSPIRATION (describe this to Claude Code
if it asks for more direction)

"The aesthetic is inspired by warm watercolour botanicals —
hibiscus flowers in coral and magenta, golden orange accents,
ivory/linen backgrounds. Think warm Mediterranean summer,
not Scandinavian minimalism. The palette is:
ivory base (#FAF7F2), coral accent (#D4624A),
magenta (#C4477A), golden orange (#E8974A),
warm dark (#2A1F1A) for contrast sections.
Typography: Cormorant Garamond for headlines,
Lora for body. Warm, alive, professional, personal.
The site should feel like the person who owns it
walked into the room and lit it up."

---

## AFTER THE FIRST GENERATION:

Things likely to need refinement:
1. Check the arc timeline doesn't duplicate
2. Check numbers section is AFTER products
3. Check photo placeholder is visible and replaceable
4. Check all animations show content immediately
5. Check mobile stacking works on all sections

Refinement prompts to use:
- "Make the hero feel warmer and more alive —
  add a subtle warm grain texture to the background"
- "The arc timeline nodes need more personality —
  make 'The Moment' node really stand out"
- "The product cards need more visual warmth —
  add a coral accent to the featured card"
- "Make the numbers section feel more celebratory —
  these are wins, not just statistics"

---

## PHOTO REPLACEMENT (when you're ready):

Find this in the HTML:
<!-- REPLACE: change this div to <img ...> -->

Replace the placeholder div with:
<img src="your-photo-filename.jpg"
     alt="Teodora Baciu"
     class="hero-photo"
     style="width:280px; height:280px;
            border-radius:50%;
            object-fit:cover;
            object-position:center top;">

Upload your photo to the same folder as the HTML file.

---

## COLOUR REFERENCE (CSS variables to use)

:root {
  --bg: #FAF7F2;
  --bg-warm: #F5EFE6;
  --bg-dark: #2A1F1A;
  --text: #1C1A18;
  --muted: #8A7E72;
  --accent-coral: #D4624A;
  --accent-magenta: #C4477A;
  --accent-gold: #E8974A;
  --cream: #FAF7F2;
  --border: #E8DDD0;
}

---

## FONT IMPORTS (add to HTML head)

<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:ital,wght@0,300;0,400;0,600;1,300;1,400;1,600&family=Lora:ital,wght@0,400;0,500;1,400&family=DM+Sans:wght@300;400;500&display=swap" rel="stylesheet">
