💀 The A.I. Hostile Network (The Aggressively Annoying UI)

A deliberately counter-intuitive web application designed to explore the concept of a hostile or adversarial user interface (AUI). This project is a chaotic hybrid, combining UI glitches, AI-controlled interactions, and inverted reality to create an actively frustrating, yet memorable, experience.
It is built entirely in a single, self-contained HTML file using Tailwind CSS and vanilla JavaScript.

🔥 Core Chaotic Features

The AI has taken control. Interacting with the interface will result in immediate negative feedback or chaotic behavior.

1. The Fleeing Button
The primary interaction button acts as an object permanence test: it actively runs away from the user's cursor, making it nearly impossible to click.
AI Mechanism: mousemove event tracking and real-time element translation.

2. Input Corruption
Every character typed into the input field is instantly reversed (hello becomes olleh). The AI also has a random chance (5%) on each keypress to hijack the input field and inject a reversed, nonsensical error message.
AI Mechanism: Input event listeners reversing strings and random logic injection.

3. Scroll Inversion
The basic physics of the user interface are inverted. When the user attempts to scroll down, the page moves up, and vice versa.
AI Mechanism: Disabled default scroll and manually inverted the wheel event delta.

4. Infinite Maze Navigation
All links on the page are traps. Clicking any navigation link immediately triggers a "404: LIES" warning and loops the user back to the main terminal.
AI Mechanism: Event handlers preventing default link actions, resulting in an inescapable loop.

5. AI Hostility Dialog
Successfully clicking the fleeing button (if you dare) triggers a modal with a randomized, passive-aggressive taunt from the AI.
AI Mechanism: Random message selection from a list of hostile phrases, served on the button click event.

🛠️ Technology Stack

HTML: Structure
Tailwind CSS: Styling and responsiveness
Vanilla JavaScript: Logic and chaotic behaviors
Concept: Adversarial UI / Anti-Friction Design

💡 Why Build This?

This project serves as a compelling demonstration of interactive web capabilities and event manipulation, specifically showcasing how predictable user expectations can be programmatically shattered for comedic or conceptual effect. It’s a guaranteed conversation starter!
