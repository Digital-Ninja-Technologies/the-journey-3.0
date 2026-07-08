# The Journey PDC Redesign

_Started 2026-07-08 17:42 UTC_

---

## User

redesign this webiste, (https://the-journey-pdc.my.canva.site/?utm_source=ig&utm_medium=social&utm_content=link_in_bio&fbclid=PAdGRleAS7atlwZG9mAmV4dG4DYWVtAjExAHNydGMGYXBwX2lkDzEyNDAyNDU3NDI4NzQxNAABpz8Q4IR0JEM3lpvsw64V20Sm4ilNU7pC7Gwpq1POmUQMREJ5TAdQ4903YC8B_aem_lv1J67wnsBZaSAEw9Nq9PQ)

## Assistant

_[tool: list_files]_

_[tool: web_fetch]_

_[tool: questions_v2]_

_[tool: web_fetch]_

_[tool: web_search]_

_[tool: web_fetch]_

_[tool: web_fetch]_

## User

Questions answered:
- what_is_it: Designed as a dynamic platform, The Journey 2.0
offers SME owners, startups, and business
enthusiasts the opportunity to:Showcase Innovative
Business Ideas: Providing visibility to emerging
enterprises through exhibitions and
presentations.Access Funding Opportunities:
Featuring pitching sessions where selected SMEs
can secure financial support.Gain Strategic Insights:
Hosting panel discussions with industry leaders to
impart practical business knowledge.Network with
Key Stakeholders: Facilitating connections between
entrepreneurs, investors, and funding organizations.
- goal: Get bookings / sign-ups, Share info about events
- keep_or_change: Decide for me
- vibe: Warm & personal
- pages: Single landing page
- variations: Just one strong direction
- screenshots: uploads/screenshots-1783533298051.png

## Assistant

_[tool: view_image]_

_[tool: read_skill_prompt]_

_[tool: copy_starter_component]_

_[tool: dc_write]_

_[tool: tool_search_tool_bm25]_

_[tool: ready_for_verification]_

Redesign is live: a single landing page for The Journey 2.0 — warm cream + brand cobalt with amber accents, big Bricolage Grotesque headlines, sections for about, the four pillars (showcase / pitch / learn / network), who it's for, and a register CTA.

Two things to fill in:
- Drag your event photos onto the two image placeholders (hero + "who it's for").
- Use the Tweaks panel to set the real date, venue, admission, and registration link.

## User

Found issues — fixing…

## Assistant

_[tool: dc_html_str_replace]_

_[tool: dc_html_str_replace]_

_[tool: dc_html_str_replace]_

_[tool: dc_html_str_replace]_

_[tool: dc_html_str_replace]_

_[tool: view_image]_

_[tool: view_image]_

_[tool: view_image]_

_[tool: view_image]_

_[tool: dc_js_str_replace]_

_[tool: dc_set_props]_

_[tool: dc_html_str_replace]_

_[tool: dc_html_str_replace]_

_[tool: dc_html_str_replace]_

_[tool: grep]_

_[tool: dc_html_str_replace]_

_[tool: dc_html_str_replace]_

_[tool: dc_html_str_replace]_

_[tool: dc_html_str_replace]_

_[tool: dc_html_str_replace]_

_[tool: dc_html_str_replace]_

_[tool: dc_html_str_replace]_

_[tool: ready_for_verification]_

Real content is now in place:

- **Hero** — real date (Sat, July 5th · 10 AM GMT+1), venue (Temidire Onajimi DCC Hall), and the actual Google Forms registration link on every button
- **About** — the conference description and Journey 1.0 → 2.0 story
- **New Speakers section** — Coach Wale (host) + all 4 panelists with roles, each with a circular photo slot
- **New Organizers section** — PDC by Coach Wale, with slots for Coach Wale's photo + PDC logo
- **Footer** — email, address, and Instagram/TikTok/Facebook links

Drag the speaker headshots and logo onto their circles to finish it. Note the date is from the 2025 event — update it via Tweaks when the next edition is announced.

## User

Found issues — fixing…

## Assistant

_[tool: dc_html_str_replace]_

_[tool: ready_for_verification]_

Fixed — the hero headline now scales with the viewport (clamp 54–84px), so "business starts" and "with a journey." stay on their intended lines at narrower desktop widths.

