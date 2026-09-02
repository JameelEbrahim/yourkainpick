# Your Kain Pick — Project Context

## Product Purpose
A lightweight Filipino food randomizer. The user sets a budget; Your Kain Pick chooses a fast-food or quick-service restaurant and a realistic order that fits the budget.

## Audience
People in the Philippines who are tired of deciding what to eat and want a quick food suggestion based on what they can spend.

## Brand
Your Kain Pick

## Tagline
You set the budget. We pick the food.

## Hero Copy
WAG KA NANG MAG-ISIP.

Sabihin mo lang magkano. Kami na bahala.

## Visual Direction
Filipino food editorial + modern consumer product. Warm, confident, direct, appetizing, contemporary, distinctly Filipino, practical, memorable. Strong typography, generous whitespace, authentic food photography, restrained surfaces and motion.

## Colors
- Primary: #F97316
- Primary dark: #EA580C
- Background: #FFF7ED
- White: #FFFFFF
- Text: #1C1917
- Muted: #78716C
- Accent yellow: #FACC15
- Success: #16A34A
- Accent light: #FED7AA

## Page Structure
1. Header
2. Hero + budget interaction + food photography
3. Recommendation result
4. Larger-budget multiple picks
5. How It Works
6. About/footer

## Copy Direction
Natural Filipino/Taglish. Short, confident, conversational, understated and human. Avoid corporate marketing, forced slang, stereotypes, generic AI copy and excessive slogans.

## Functionality
- Budget input from ₱50 to ₱5,000.
- Quick budget buttons: ₱100, ₱250, ₱500, ₱1,000, ₱2,000, ₱5,000.
- Validate empty, invalid, below-minimum and above-maximum budgets.
- PICK MY KAIN runs a short restaurant-name randomizer before revealing a result.
- Results always satisfy total <= budget.
- Roll Again avoids immediately repeating the same restaurant/order where possible.
- Change Budget returns focus to the budget input.
- ₱50–₱1,499: 1 result.
- ₱1,500–₱2,999: 3 options.
- ₱3,000–₱4,999: 4 options.
- ₱5,000: 5 options.
- View Pick opens a full recommendation.
- Approximate pricing only; no live availability, ordering, payment, checkout, ratings or reviews.

## Pricing Disclaimer
Prices may vary by restaurant location and availability.

## Technical Constraints
One self-contained index.html using semantic HTML, CSS and vanilla JavaScript. No React, Next.js, Tailwind, npm, build system, unnecessary dependencies or vercel.json.

## Anti-Slop Rules
No emojis or decorative Unicode symbols. No glassmorphism, glow, neon, excessive gradients, floating blobs, random abstract shapes, excessive shadows, excessive rounded cards/pills, giant rounded buttons, excessive icons, confetti, particles, cursor-following effects, unnecessary parallax, excessive hover animation, meaningless illustrations, fake 3D, complex backgrounds or generic SaaS/dashboard styling.

## Current Truth
The working product is the budget-to-food recommendation flow described above. Keep the experience simple: the product removes the question “Anong kakainin?” rather than showcasing unnecessary features.
