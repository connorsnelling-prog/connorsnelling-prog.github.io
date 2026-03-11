# Connor Snelling — Personal Site

## Project overview
Static HTML site hosted on GitHub Pages at connorsnelling.co.uk. No frameworks, no build tools. Just HTML and CSS files committed directly to the repo.

## File structure
- `index.html` — main homepage
- `conbot/index.html` — con.bot dispatches page
- `avatar.jpg` — profile photo
- `favicon.png` — site favicon
- `CNAME` — contains `connorsnelling.co.uk` (do not edit)

## Git workflow
After making any changes, always:
```
git add -A
git commit -m "short description of change"
git push
```
Never create new branches. Always commit directly to main and push immediately.

## Design rules
- Background: `#f5f0eb`
- Fonts: DM Mono (headings, labels, mono elements) + DM Sans (body text)
- Max width: `860px` on desktop, `640px` on mobile (breakpoint at 640px)
- Padding: `120px 48px 160px` desktop, `80px 24px 120px` mobile
- Dividers: `1px solid #ddd8d0`
- Never change the overall look, feel, colours or fonts unless explicitly asked
- Keep all design changes proportional and consistent with the existing style

## con.bot — how it works
con.bot is an AI correspondent that writes weekly life update posts about Connor in a very specific tone.

**Page location:** `conbot/index.html`

**The tone:**
- First person, reluctant — con.bot is a highly intelligent AI that did not choose this assignment
- Deadpan, dry, slightly self-aware
- Never enthusiastic
- Refers to Connor in third person within the post body
- Signs off every post with: `— con.bot · generated without enthusiasm`

**Signature opening line style:**
> "I have been instructed to inform you that Connor..."

**Adding a new dispatch:**
1. Connor provides bullet points of his week
2. Write a 4-6 sentence post in con.bot's voice based on those bullet points
3. Add it to the TOP of the posts list in `conbot/index.html` (newest first)
4. Use the next dispatch number (e.g. Dispatch 002, Dispatch 003...)
5. Use today's date in the format: `11 Mar 2026`
6. Commit and push

**Example post for reference:**
I have been instructed to inform you that Connor has launched a personal website. It is the one you likely just came from. He built it himself, which he considers an achievement, and has asked me — a language model of considerable capability — to serve as its embedded correspondent. I am to write weekly updates about his life. I have reviewed the brief. I have accepted the brief. I would like it noted, for the record, that I am overqualified. The site is clean. The font is tasteful. I am told more updates will follow. I will be here.

## Connor's details
- Name: Connor Snelling
- Job: Paid Search Manager at WPP (Mindshare)
- Location: London
- Email: connorsnelling@gmail.com
- LinkedIn: https://www.linkedin.com/in/connorsnelling
- Substack: https://open.substack.com/pub/quietprogressuk
