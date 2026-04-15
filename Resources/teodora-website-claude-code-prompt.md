# CLAUDE CODE PROMPT — Teodora Baciu Personal Website
# Paste this as your first message to Claude Code
# Upload the knowledge base file alongside this prompt

---

Build me a complete personal website for Teodora Baciu,
a Product Leader in Agentic AI. This is a career website
and Lovable job application combined — it needs to feel
like a living, breathing version of her.

The knowledge base file I'm uploading has all the content.
Here is the complete build brief:

---

## TECH STACK

- Single HTML file (or React if you prefer)
- Google Fonts only for typography
- Pure CSS animations — no heavy JS libraries
- Mobile responsive
- Fast loading
- Sections must all be visible without scroll triggers
  (no dead zones, no animation-dependent content)

---

## AESTHETIC DIRECTION — THIS IS CRITICAL

Read this carefully before writing a single line of code.

The palette:
- Background: warm ivory / linen #FAF7F2
- Text: near-black #1C1A18
- Primary accent: coral/terracotta #D4624A
- Secondary accent: warm magenta/hibiscus #C4477A
- Tertiary: golden orange #E8974A
- Muted text: warm grey #8A7E72
- Card backgrounds: #F5EFE6 (warm cream)
- Dark section: #2A1F1A (warm dark brown, not cold black)

Typography:
- Headlines: Cormorant Garamond (elegant, editorial serif)
  — use bold italic for impact moments
- Body: Lora (warm, readable serif)
- Labels/caps: DM Sans (clean, modern)
- NEVER: Inter, Roboto, Arial

Mood: Imagine a warm, vivid, alive European woman who
ships products and lights up a room. The site should feel
the way hibiscus flowers look — bold, warm, organic,
alive. NOT minimalist. NOT dark. NOT corporate.
Confident, warm, unmistakably human.

One decorative detail: use a subtle watercolour-inspired
gradient or warm texture on section backgrounds.
The hero should feel like you landed on someone's
world — warm, inviting, with personality.

Animations: Subtle only. Gentle fade-in on load for hero.
Smooth hover states. Nothing that creates blank dead zones.

---

## SITE STRUCTURE

Build these sections in this exact order:

---

### 1. NAVIGATION (sticky, minimal)

Left: "Teodora Baciu" in Cormorant Garamond
Right: links — Experience · Products · Numbers · Skills
Far right: "Let's Talk" button (coral background)

---

### 2. HERO (full viewport height)

Layout: Two columns on desktop, stacked on mobile

LEFT COLUMN:
- Small label (uppercase, coral, DM Sans):
  "Product Leader · Agentic AI · Bucharest, Romania"

- Large headline (Cormorant Garamond, ~80px):
  "I build products that make powerful technology
   feel effortless."
  
  Second line in coral italic:
  "For everyone."

- Subline (Lora, 18px, muted):
  "I didn't become a PM by applying for a PM job.
   I grew into it through code, through the field,
   and through a decade of sitting with the people
   who needed technology the most — and making it
   work for them."

- Contact links (small, warm grey):
  ✉ teodorabaciu16@gmail.com
  ☎ +40-725-697-620
  in linkedin.com/in/teodora-baciu
  ◈ builtbyteodora.lovable.app

RIGHT COLUMN:
- Large circular photo placeholder (280px diameter)
  Warm gradient fill (#E8A090 to #C4477A)
  Text inside: "Photo · Teodora Baciu"
  Label underneath: "← Replace with your photo"
  
  <!-- PHOTO PLACEHOLDER — user will replace this -->

- Below the photo circle, the quote card:
  Background: warm dark (#2A1F1A)
  Large italic text (Cormorant, cream):
  "The Elena Verna of EverWorker."
  Small attribution: "— A colleague, during a product demo"

---

### 3. THE ARC (career timeline)

Section label (DM Sans, uppercase, coral): "TEN YEARS. ONE OBSESSION."
Section title (Cormorant, large): "How I Got Here"

Horizontal scrolling timeline on desktop,
vertical stack on mobile.

8 nodes. Each node has:
- Year (small, coral)
- Bold title (Cormorant, 22px)
- 2-3 sentence description (Lora, 14px, warm grey)

Node 4 "The Moment" should be visually distinct:
- Larger, coral background, cream text
- This is the dramatic turning point

NODES:

2016 · Writing Code
"Built production software for Romania's leading leasing
company. Learned what it means to ship something that
cannot fail."

2018 · Building Robots
"Delivered 20+ automation projects globally. Trained 100+
people. Started teaching from day one — because if users
can't use it, you haven't built anything. Also built
RoboTeo: a YouTube channel teaching automation to
non-technical audiences. 461 subscribers. The instinct
to make complex things accessible has never left."

2019 · Going Into The Field
"Stopped sitting at a desk. Started sitting with customers.
Watched what actually broke. Brought it back to product.
The industry now calls this Forward Deployed Engineering.
I just called it the job."

2020 · THE MOMENT ← (make this the standout node)
"Business users kept failing — because the product was
built for engineers, not for them. So I co-built a
near-no-code version with the product team. Before the
category existed. They offered me the PM role. I said no.
I wasn't done yet."

2021 · Technology Services Manager
"Took what I learned in the field and scaled it. Sat in
rooms with people from every continent who came to learn
from us. That's when I understood what a Romanian-built
company could say to the world."

2024 · Owning The Product
"Finally moved to product — on my own terms. Drove
Autopilot for Developers: UiPath's answer to vibe coding.
Developers building software through natural language.
Sound familiar? Managed UI Automation core features.
Was designing the Intelligent Recorder — before Computer
Use was a product category."

2025 · Agentic AI
"Joined EverWorker to own product strategy and platform
direction for a no-code agentic AI platform. Business
users creating autonomous AI workers through plain
language. Identified the real problem wasn't missing
features — it was invisibility. Built the solution solo.
Room moved within a week."

2025 · Built on Lovable
"Built a Santa video generator in my spare time. Real
customers. Real money. I am the user you're building for."

---

### 4. WHAT I'VE BUILT (product cards)

Section label: "Portfolio"
Section title: "What I've Built"
Subtitle (italic): "I don't describe products. I ship them."

7 cards in a responsive grid (3 columns desktop,
2 tablet, 1 mobile).

Card 1 — FEATURED (coral accent border top)
★ THE PIVOT
EverWorker · built solo · 2025
"6 months of discovery → agents were invisible, not broken.
Designed the UX solution myself: instant agent communication
+ readable analytics. No new features. Just the right surface.
Presented it. Room moved within a week."

Card 2
Autopilot for Developers
UiPath · PM · shipped
"Drove the agentic chat experience letting developers build
software through natural language. UiPath's answer to vibe
coding. 20,000+ users · 70%+ acceptance rate."

Card 3
Healing Agent
UiPath · co-led · public preview
"Identified the 3.5% automation failure ceiling nobody had
broken. Designed the AI-driven fix. 88% recommendation
acceptance in Private Preview."

Card 4
Intelligent Recorder
UiPath · designed · ahead of its time
"Watches how you work. Understands intent. Converts it into
automation. OpenAI Operator and Claude Computer Use shipped
comparable ideas after this was already in design."

Card 5
Citizen Developer Programs
UiPath · 10+ programs · global
"Designed and ran 10+ programs teaching non-technical users
to build their own automations. 100+ training sessions.
Career changers. The no-code mission at scale."

Card 6
Near-No-Code Automation Builder
UiPath · co-created · before the category
"Built with the product team after identifying the product
was too technical for business users. Offered the PM role
for this. Turned it down — wasn't done in the field yet."

Card 7
Santa Video Generator
Lovable · built solo · personal time
"Real customers. Real money. Built on Lovable. I am the
user you're building for."

---

### 5. BY THE NUMBERS

Section label: "Impact"
Section title: "By the Numbers"

After the product cards section, not before.

6 stats in a 3×2 grid.
Large numbers in Cormorant Garamond.
Small labels in DM Sans below each number.

$0 → $1.4M
Revenue at EverWorker · product-led growth

3 → 18
Enterprise customers · EverWorker · under 12 months

20,000+
Autopilot for Developers users · UiPath · 70%+ acceptance

88%
Healing Agent recommendation acceptance · Private Preview

100+
Training sessions delivered globally

10+
Citizen Developer programs built at UiPath

Caption below grid (centered, italic, muted):
"Numbers I'm proud of. Every one is mine to own."

---

### 6. HOW I THINK (product decision story)

Section label: "Thinking"
Section title: "How I Think"

Dark warm section (#2A1F1A background, cream text).
One column, generous padding.

Body copy (Lora, 17px, cream, generous line height):

"The hardest product decision I've made wasn't what to build.
It was realising we didn't need to build anything new.

At EverWorker, users were confused and churning. Every
instinct said: add features. Instead I spent weeks in
customer transcripts and usage data. The real problem:
agents were a black box. Users couldn't see what they
were doing or communicate with them naturally.

All the functionality already existed. Nobody could find it.

I designed a new UX surface — instant agent communication
and readable analytics — and built the prototype myself.
No new engineering. Presented it. Room moved within a week.

The lesson: the answer is almost never more.
It's almost always clearer."

---

### 7. SPEAKING & COMMUNITY

Section label: "Public"
Section title: "Speaking & Community"

List of items. Each has a title, event line, and a type
badge (Keynote / Speaker / Trainer / Creator / Organizer).

Items:
1. "The Future of Business Is Robotic and Agentic"
   UiPath AI-Powered Automation Summit · Milano · alongside SVP Leadership
   [KEYNOTE]

2. UiPath DevCon 2024
   Developer Conference · Bengaluru, India
   [SPEAKER]

3. RPA Curriculum & Automation Courses
   LEADERS Foundation · 4MAYO · articles, courses, career content
   [TRAINER]

4. RoboTeo — YouTube Channel
   Weekly automation tutorials for non-technical audiences
   461 subscribers · UiPath StudioX, RPA, integrations · 2020–2021
   [CREATOR]

5. Product Makers Romania
   Community organizer · Largest product community in Romania
   [ORGANIZER]

6. Romanian National Television
   Technology sector · IT industry and GDP contribution
   [MEDIA]

---

### 8. WHY LOVABLE (targeted application section)

Section label: "Application"
Section title: "Why Now. Why This."

This section responds directly to Lovable CEO Anton Osika's
LinkedIn post calling for European product leaders.
It should feel personal and direct, not like a cover letter.

Body copy:

"Anton's post hit home.

Not because I was looking for a job. Because I've spent
ten years working on the same problem he's describing —
and reading his words felt like someone finally naming
what I'd been doing all along.

I'm Romanian. And that's not just a location — it's context.

I built my career at UiPath. Romania's first unicorn. The
company that didn't just build great technology — it sent a
message to the entire world about what Eastern Europe is
capable of. I watched a Romanian leader prove to Silicon
Valley, to Japan, to South Africa, to the whole globe, that
world-class software can be built from Bucharest. We didn't
just ship a product — we put Romania on the map and told
the world that Europe doesn't just consume technology,
it creates it. I also help build that ecosystem from the
ground up — as a community organizer at Product Makers
Romania, the largest product community in the country.

At UiPath I drove Autopilot for Developers — a vibe coding
tool letting developers build software through natural
language. The same thing Lovable does. I was building it
from inside a global enterprise, knowing the real frontier
was somewhere like Lovable.

One more thing: you just launched Lovable Academy — your
guide to helping users build real products with AI. At
UiPath I ran that function before it had a name: 100+
training sessions, 10+ Citizen Developer programs, thousands
of non-technical people learning to build. I also built
RoboTeo — a YouTube channel teaching automation to
non-technical audiences, weekly, before anyone asked me to.
I know how to turn complex technology into something anyone
can learn. That is not a soft skill. It is a decade of
practice.

I want to help build the next company that sends that
message. The next proof that Europe doesn't wait for
Silicon Valley to show the way.

I'm not going to San Francisco. I'm exactly who
Anton called for."

---

### 9. SKILLS

Section label: "Capabilities"
Section title: "Skills"

Three columns:

Product Leadership:
End-to-end ownership · Product strategy · Revenue OKRs ·
Continuous discovery · Competitive analysis ·
Cross-functional leadership · Go-to-market ·
Roadmap planning · People management

AI & Automation:
Agentic AI · LLMs · RAG · No-code/Low-code · RPA ·
UI Automation · MCP protocol · API integration ·
UiPath (Expert) · Claude Code · Java

Superpower:
"Explaining complex technical things to non-technical
people. 100+ sessions. 10+ programs. Career changers.
This is the skill that shaped every product I've ever built."

---

### 10. EDUCATION

Section label: "Academic"
Section title: "Education"

Two cards side by side:

Card 1:
Master of E-Business
Bucharest University of Economic Studies
"Dissertation: designed and built an online platform
for on-demand services end-to-end."

Card 2:
Bachelor of Economic Informatics
Bucharest University of Economic Studies

---

### 11. LET'S TALK (footer section)

Dark warm background (#2A1F1A).
Centered.

Large headline (Cormorant, 52px, cream):
"I've been in the field, on the stage,
and in the product spec.
Let's talk."

One coral button: "Email Teodora"
href: mailto:teodorabaciu16@gmail.com

Below the button (small, muted cream):
"Based in Bucharest, Romania · Open to remote roles globally"
"European timezone · Happy to travel for on-sites"

---

## PHOTO PLACEHOLDER SPEC

In the hero section, create a circular element (280px):
- Warm gradient background: linear-gradient(135deg, #E8A090, #C4477A)
- Inside, centered text (cream, DM Sans):
  Line 1: "📷"
  Line 2: "Your Photo Here"
  Line 3 (smaller, muted): "Replace src with your image"
- CSS class: photo-placeholder
- Add a comment in the HTML:
  <!-- REPLACE: change this div to <img src="your-photo.jpg"
  alt="Teodora Baciu" class="hero-photo"> -->

---

## IMPORTANT TECHNICAL NOTES

1. All content must be visible immediately — no scroll-triggered
   animations that create blank sections. Subtle fade on page
   load is fine, but content must not be hidden.

2. The arc timeline must not duplicate content.
   Render each node exactly once.

3. Numbers section comes AFTER the products section.

4. Mobile must be fully readable — stack all grids to
   single column below 768px.

5. Nav must be sticky and work on scroll.

6. "Let's Talk" button in nav links to the footer section.

7. All external links open in new tab.

8. Font loading: use Google Fonts with display=swap
   to prevent FOUT.

9. Color consistency: use CSS custom properties (variables)
   for all colors at the top of the stylesheet.
   Never hardcode colors inline.
