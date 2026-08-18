Project: GRAVITY — Mind Weightless Architecture
Developer: Ritika Yadav
1. Why this ingestion strategy over the obvious alternative you rejected?

Look, the obvious path would've been a standard grid layout—clean, symmetrical, predictable. Everyone does that. But that's exactly the problem: it would've been completely wrong for what GRAVITY is trying to be.

I deliberately broke the grid because I wanted the interface itself to feel like weightlessness. When you open the page, the hero is split unevenly (1.2/0.8), the cards are all rotated at different angles, the watermarks float behind everything. Nothing is perfectly aligned. And that's intentional.

Think about it—gravity is about order, predictability, structure. Anti-gravity is the opposite. It's chaotic, floating, non-linear. If I had built a perfectly aligned, symmetrical page, I'd be selling the opposite of what this product is. The visual friction, the off-kilter rotations, the way elements sit slightly wrong—that's the point. It's supposed to make you feel slightly unsettled, like the page itself is defying physics.

The alternative would've been safer and easier to code, but it would've been dishonest to the brand. This way, the design is the demonstration of the product's promise.

2. One trade-off you made under the time limit, and what you'd do with a real week.

The physics arena. Without question.

Right now, the "Zero-G Thought Playground" works—you can drag nodes, they bounce, you can flip gravity on and off. But it's basic. Barebones. It's the difference between a sketch and a finished piece.

What I got done:

Working drag-and-toss mechanics

Gravity toggle (zero-G / downward)

Boundary collision with bounce

Basic velocity damping

What I wanted to build:

Nodes that actually collide with each other and react realistically

Spring connections between nodes that stretch and snap

The cursor creating a gravitational pull field that distorts everything

Particles trailing behind fast-moving nodes

Persistent memory of node positions between sessions

Multi-touch so this works on tablets too

With a proper week, I'd implement a lightweight physics engine (Matter.js or roll my own Verlet integration) and turn that arena into something genuinely useful—not just a tech demo, but a workspace where ideas can literally collide and combine in unexpected ways. That's the vision. The current version is just the foundation.

3. Where did you use AI tools, and what did you personally verify or change afterward?

I'll be honest—I used AI for scaffolding and nothing else. The boilerplate stuff that eats time but doesn't require creative thinking.

What AI helped with:

Initial HTML skeleton (the basic structure, headings, containers)

First draft of copy (taglines, descriptions—which I completely rewrote anyway)

CSS variable setup (colors, fonts, basic values)

But literally everything meaningful came from me:

Every single visual decision—the specific terracotta (#C85A32), that exact mustard yellow, the algae green—I picked those colors by hand. I tested them in both Solar and Zero-G modes, adjusted contrast, made sure they hit the right emotional tone. AI gave me generic suggestions; I threw them out and built the palette from scratch.

The layout? That's all me. The asymmetrical grid, the rotated elements, the card tilt interactions—I coded every transform and rotation value manually. AI doesn't understand why a 2.2-degree rotation feels different from 2.5 degrees. I do.

The physics engine in the arena—the drag-and-toss, the velocity calculations, the gravity toggle—I wrote that code myself. No AI shortcuts there. The particle field animation, the wave effect on the flow state card, the rotary dial interaction—all hand-coded.

And the tuning? The cursor hover scaling, the timing of the momentum calculations, the speed of the card tilt response—all refined through dozens of testing iterations. AI couldn't have told me that the 0.96 damping coefficient feels more natural than 0.95. That came from feel.

So yeah, AI saved me maybe an hour on boilerplate. Everything else—the soul of this page—that's mine.

