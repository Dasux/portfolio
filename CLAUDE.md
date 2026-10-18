# Task: Refine my portfolio homepage to look more professional and engineering-focused

You are working directly in my existing portfolio repository:

https://dasux.github.io/portfolio/

Your task is to modify the existing website, not create a new website from scratch.

## Objective

Refine the homepage so it feels like a credible engineering portfolio for a final-year B.Tech Electronics and Communication Engineering student pursuing embedded systems, digital design, and aerospace/space technology opportunities.

The current site uses a dark terminal-inspired aesthetic, neon-green accents, JetBrains Mono for headings, and Inter for body text. Preserve this identity, but make the presentation more restrained, mature, and professional.

The desired impression is:

"An engineering student documenting real work, technical experiments, and things he's learning."

Avoid the impression of:

"An aspiring tech entrepreneur trying too hard to look impressive."

Prioritize technical substance, readability, visual hierarchy, and credibility over decorative effects.

## Step 1 — Inspect before editing

Before making changes:

1. Inspect the existing homepage HTML, CSS, JavaScript, and project-card components.
2. Identify how the current navigation, About, Projects, Skills, and Contact sections are implemented.
3. Inspect existing assets and identify the resume PDF, project thumbnails, and repository URLs.
4. Reuse the existing design system and components wherever practical.
5. Do not invent project details, repository URLs, statistics, skills, achievements, or resume content.

Keep changes scoped to the homepage and any shared styles or assets genuinely required by the task. Avoid unrelated rewrites.

## Step 2 — Reorder the homepage

Change the main content order to:

1. Hero / introduction
2. Projects
3. About Me + Resume + Selected Repositories
4. Technical Skills, if currently present
5. Minimal footer with contact and social links

Update the navigation links and section IDs to match the new order.

Keep the hero relatively compact. It should establish my name, current academic background, and engineering interests without excessive self-promotion.

Use straightforward language. Avoid grandiose taglines, motivational statements, excessive first-person declarations, and claims that make me sound more experienced than I am.

## Step 3 — Replace the Contact section with an extended About Me section

Remove the existing Contact section as a standalone, prominent homepage section and replace it with an extended About section.

This new section must have a two-column layout on desktop.

### Left column: Selected repositories

Create a vertically stacked list of compact, GitHub-inspired repository cards.

The cards should visually resemble understated repository entries, not marketing cards.

Each card should contain only relevant information that already exists in the repository or can be verified from the linked project:

- Repository or project name.
- A short, factual description.
- Relevant language, technology, or topic labels, where supported by the actual project.
- A link to the actual GitHub repository.

Use real repositories from my GitHub account:

https://github.com/Dasux

Prioritize repositories that demonstrate relevant engineering work. Inspect the available repositories and select suitable existing projects rather than inventing new ones.

Potential areas to investigate include experimental rocketry, RHEL/Cadence lab deployment, embedded systems, digital design, and electronics.

Only include repositories that actually exist and have meaningful content. If a repository is unfinished, describe it accurately rather than implying that it is complete.

Design requirements:

- Stack the cards vertically.
- Keep them compact and information-dense.
- Use subtle borders, restrained green accents, and consistent spacing.
- Use small language or topic labels only when factually supported.
- Provide clear hover and keyboard-focus states.
- Make the repository name and link easy to identify.
- Avoid excessive icons, animations, glowing effects, and large decorative graphics.

The purpose is to make the work easy to inspect, not to decorate the page.

### Right column: Resume card

Create a resume-preview card using the same basic visual language as the existing project cards.

Use the existing resume page and asset if available. The expected existing resources are:

- Resume page: `resume.html`
- Resume PDF: `assets/anirban_das_resume.pdf`

Verify that these files exist before using their paths. If the actual paths differ, use the correct existing paths instead.

The card should feature a vertical preview of the actual resume, not a generic illustration or a fabricated document.

Visual treatment:

- Display the resume preview prominently within the card.
- Use a subtle dark gradient or fade near the bottom of the preview.
- Overlay the text "Resume Preview" near the bottom.
- Keep the surrounding card clean and understated.
- Make the card clickable, linking to the existing resume page or verified PDF.
- Make the interaction accessible to keyboard users and provide an appropriate accessible label.

Do not recreate the resume's contents in HTML. Use the actual existing document or an existing preview asset.

On desktop, the repository list should occupy the left column and the resume card should occupy the right column. Align their top edges.

On smaller screens, stack the columns cleanly, with the repository list first and the resume card afterward.

### About Me copy

Include a concise biography within this section, positioned above or adjacent to the two-column layout without overwhelming it.

The copy should communicate that I am a final-year B.Tech ECE student at GSV Vadodara interested in electronics, embedded systems, Linux, digital design, and aerospace engineering.

Use a grounded, factual tone. Describe what I work on and what I am learning rather than making broad claims about my ambitions or capabilities.

Do not invent employment experience, qualifications, completed projects, or expertise.

## Step 4 — Visual refinement

The current aesthetic should remain recognizable, but the overall result should feel calmer.

Keep:
- Dark background.
- Existing typography, where practical.
- Restrained neon-green accents.
- Existing project-card design language.
- Clear technical headings and links.

Reduce:
- Unnecessary glow and neon effects.
- Excessive borders, boxes, and decorative separators.
- Overly dramatic typography.
- Unnecessary animations and transitions.
- Repeated descriptions and self-promotional copy.
- Anything that competes visually with the project content.

Do not redesign every component simply to make the code look cleaner. Prefer targeted CSS and HTML changes.

Maintain consistent spacing, readable contrast, and a clear hierarchy between section headings, descriptions, metadata, and links.

## Step 5 — Responsive design and accessibility

Verify the layout at desktop, tablet, and mobile widths.

Requirements:
- No horizontal overflow.
- Repository cards remain readable on narrow screens.
- The resume preview maintains a sensible vertical aspect ratio.
- Navigation links point to the correct sections.
- Interactive elements have visible keyboard-focus states.
- Text and links have sufficient contrast.
- Respect reduced-motion preferences if animations remain.
- Do not introduce unnecessary JavaScript dependencies.

Preserve existing site functionality.

## Step 6 — Validate the result

After implementation:

1. Check for broken asset paths and links.
2. Check that the resume card opens the correct resource.
3. Check that all selected GitHub links point to real repositories.
4. Check that section navigation works after reordering.
5. Check the desktop and mobile layouts.
6. Check for console errors or obvious HTML/CSS issues using the available project tooling.
7. Confirm that no project claims or skill descriptions were invented.

If browser automation or screenshot tooling is available, inspect the rendered homepage at desktop and mobile sizes. Do not claim visual validation if you could not actually perform it.

## Deliverables

Make the changes directly in the existing project.

When finished, report:

1. Files modified.
2. Homepage changes implemented.
3. Repositories selected and why.
4. Any assumptions or missing assets.
5. Tests and visual checks actually performed.
6. Anything I need to review manually before deploying.

Do not merely describe the proposed changes. Implement them.

The final result should look like a restrained, technically credible engineering portfolio — not a startup landing page, personal-brand campaign, or generic AI-generated developer template.
