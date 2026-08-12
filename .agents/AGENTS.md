# Workspace Customization Rules for Antigravity Coding Assistant

## File Editing Rules
- **Direct Modification Only**: You MUST edit files directly using built-in file editing tools (such as `replace_file_content` or `write_to_file`).
- **No Automation Scripts**: NEVER write or execute Python, JavaScript, or other scripting code to perform search-and-replace or automate content changes on project files. Edits must be direct so they are clear to review.
- **No CLI Batch Replacements**: Do not use command-line utilities (like PowerShell `Set-Content`, `sed`, or batch replace tools) to modify file contents. Every file change must be done via the IDE's built-in file editing tools to allow the user to review and approve/reject the changes.

## Neighborhood Reference Standard
- **Al Qadisiyah Reference**: The Al Qadisiyah page (`service-areas/furniture-moving-al-qadisiyah-riyadh-with-crane-service/index.html`) is the official quality, content depth, and structural strength reference for all neighborhood pages. All neighborhood pages must be optimized to match or exceed this level of content authority.

## SEO Content Guardrails for Service Areas
- **Internal Linking**: Every content section (e.g., `<section>`) in a service area page MUST contain at least two internal HTML links (`<a>` tags) naturally embedded within its paragraph/body text pointing to other neighborhood pages, blog posts, or service details. No content section should have zero links.
- **Structural Diversity**: Do NOT reuse identical section ordering, layouts, or heading structures across different neighborhood pages. To prevent search engines (like Google) from skipping indexing due to cookie-cutter template patterns, vary headers, layouts, section order, and wording styles while maintaining the same high standard of depth, quality, and word count.

## UI/UX & Visual Design Standards for Fashne-net
- **Light Theme Color Balance**: Maintain an ultra-clean light theme (`bg-slate-50`, `bg-white`) using royal blue and sky blue accents. Avoid aggressive multi-gradient text or neon glows on service cards. Use pure FontAwesome 6 icons.
- **Card Placement Relative to Images**: Position platform ecosystem cards directly BELOW image frames rather than obscuring images with floating overlays.
- **Dynamic Scroll Reveal & Fade-Out**: Interactive workflow items (such as "كيف نعمل") should use `IntersectionObserver` logic to smoothly animate (fade in and fade out) when scrolled into or out of view.
- **Borderless & Fluid Sections**: CTA and goal sections should maintain an open, fluid layout without heavy outer borders or boxed frames.
- **Favicon Links in Head**: Always include favicon link tags (`<link rel="icon" type="image/png" ...>`) inside the `<head>` of all HTML files.
- **Tone Scale presentation (No Sliders)**: When presenting brand voice or tone scales, represent the dimensions as clean, structured vertical ribbon cards with distinct side border colors, small icons, and brief tags (e.g., "نبرة قريبة ومحببة") rather than rendering active range slider bars.
- **Social Platform Grid Layout**: For platform grids (e.g., Facebook, Instagram, X), wrap each item in a vertical layout containing:
  1. A colored square container (`w-12 h-12 rounded-2xl`) containing only the social network icon, using its official brand color by default.
  2. The name/label of the platform placed separately, directly below the icon container.
  3. Constrain the containers to prevent wide horizontal stretching (e.g., using `max-w-[100px] w-full mx-auto` or `lg:grid-cols-7`).
- **Official X Icon (Twitter)**: For the platform X, always use an inline high-fidelity SVG icon for the "X" logo instead of relying on `fa-x-twitter` to guarantee reliable rendering.
- **Translucent Dark Elements in Light Themes**: If a dark element (like a terminal or programming code console) is needed on a light-themed page, avoid solid dark backgrounds (`bg-slate-950`). Instead, use a medium translucent glassmorphic shade (e.g., `bg-slate-900/80 backdrop-blur-md`) with soft borders (`border-slate-800/60`) to maintain color balance.
- **Verbatim Copy Invariance**: When the user provides explicit text copy for headings, titles, or descriptions, use it exactly as provided without summarization or editorial modification, while applying the requested visual layouts.
- **FontAwesome Rendering Compatibility**: Avoid obscure FontAwesome 6 icon sub-classes (e.g., `fa-magnifying-glass-chart`, `fa-shield-halved`) that may fail to render. Always default to universally supported classes (e.g., `fa-search` instead of search-charts, and `fa-shield-alt` instead of shield-halved).
