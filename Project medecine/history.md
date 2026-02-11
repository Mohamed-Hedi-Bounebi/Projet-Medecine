# History Log

## 2026-02-11
**User Request:**
Create a modern, professional Arabic (RTL) landing page for an organization named ATDE using pure HTML and CSS without any frameworks. The page must use dir="rtl" and Arabic content, with a clean and minimal aesthetic built around a soft purple color palette. Apply a global reset for margin, padding, and box-sizing, and use a clean sans-serif font stack such as 'Segoe UI', Tahoma, Arial. The body background should be a light gray (#f9f9f9) with dark gray text (#1a1a1a) to maintain strong readability and a professional appearance.

Design a sticky navigation bar positioned at the top using flexbox, aligning items centrally and spacing them evenly with justify-content: space-between. The navbar should have generous padding (20px 60px), a white background, and a subtle bottom border (#eee). It must remain visible while scrolling using position: sticky and a high z-index. The branding section, positioned according to RTL layout, should include a circular 60x60px logo placeholder with a light gray background and a purple border (#6d28d9), centered text inside, and fully rounded corners. Next to it, include a vertically stacked text block aligned to the right, featuring a large ultra-bold “ATDE” acronym (32px, weight 900) in deep purple (#4c1d95), with a smaller semi-bold subtitle below (13px, weight 600) in a lighter purple (#7c3aed) and slight spacing above it.

The navigation section should include horizontal links displayed in a flex container with consistent spacing. Remove default list styling and ensure a clean appearance. Each link should be bold (700), 17px in size, black in color (#1a1a1a), and without underlines. Add a smooth hover transition where the text color changes to deep purple (#4c1d95). On the far side, include a prominent “اتصل بنا” call-to-action button styled with a solid purple background (#5b21b6), white bold text, padding of 10px 25px, rounded corners (12px), and a subtle scaling hover animation with a darker purple shade (#4c1d95).

Below the navbar, create a large hero section occupying 80% of the viewport height. Center the content both vertically and horizontally using flexbox, with text centered and contained within a maximum width of 800px. Apply a soft purple gradient background from #f5f3ff to #ede9fe and add a decorative circular shape using a ::before pseudo-element, sized at 400x400px with a very light purple tint and positioned partially outside the top-right area to create depth. The hero headline should be large (4rem), ultra-bold (900), and dark indigo (#1e1b4b) with a balanced line height. The subtitle should be 1.5rem in size, purple (#4c1d95), and slightly transparent for elegance. Include a rounded pill-shaped primary action button with padding (15px 40px), bold white text, a purple background (#7c3aed), soft shadow, and a smooth hover darkening effect.

Ensure the design is responsive by adding a media query for screens below 768px. In smaller viewports, hide the navigation links and subtitle text, reduce navbar padding, and decrease the hero title size to 2.5rem while maintaining proper spacing and alignment. The overall goal is to deliver a clean, accessible, modern RTL layout with strong visual hierarchy, soft branding, smooth hover effects, and a professional NGO-style presentation.

**User Request (Update):**
add three 24px rounded boxes under the hero text featuring the following
1- a box containing the title learn about epilepsy with a sky blue and mint green nuanced border
2- a box containing the title challenge yourself with a magnta and orange nuanced border

**User Request (Update):**
Change the third box from "Share your story" to "Support our work".

**User Request (Update):**
Make the boxes span across the width of the page (responsive layout), increase height to feature graphic art, and add comments for image links.

**User Request (Update):**
Fix the navbar overlapping the hero section content, bring back the nuanced borders for the boxes, and snap the box titles to the top.

**User Request (Update):**
Update feature box borders:
1. "Learn about epilepsy" -> Sky Blue & Mint Green.
2. "Challenge yourself" -> Magenta & Orange.
3. "Support our work" -> Violet & Gold.

**User Request (Bug Report):**
The borders are not visible in the idle state. Fix the CSS to make them visible.

**User Request (New Feature):**
1. Click on Card 1 -> Scroll to "learn-panel" (Wide cards with course title, subtitle, button).
2. Click on Card 2 -> Scroll to "challenge-panel" (Wide cards with challenge title, funny subtitle, button).

**User Request (New Feature):**
Add a section before `learn-panel` titled "For whom is this site" with 4 horizontal transparent panels:
1. Patients
2. Parents
3. Healthcare Staff
4. Researchers & Financers
Each with a big icon (theme colored) and a subtitle explaining importance.

**User Request (Update):**
Link navbar tabs to specific pages:
- About Us -> `aboutus.html`
- Financing -> `financing.html`
- Learn With Us -> `learning.html`

**User Request (Update):**
1. Link "Our Events" tab to `events.html`.
2. Change `index.html` UI elements and font style to match other HTML files (using 'Cairo' font and consistent styling).

**User Request (Update):**
Make the logo image fit the logo container.

**User Request (Update):**
Change `index.html` navbar style to match other pages (rounded corners, spacing, shadows, etc.).
