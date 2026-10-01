---
name: build-audience-analysis-sheet
description: Create or update audience-analysis spreadsheets for crowdfunding, nonprofit, cultural, event, public-interest, and product campaigns. Use when the user provides project briefs, PDFs, decks, URLs, existing Excel templates, or Google Sheets and asks for audience segments, personas, psychological and behavioral profiles, communication angles, reach channels, Meta advertising interests, new-customer acquisition, lookalikes, or retargeting in an .xlsx or Google Sheets-ready format.
---

# Build Audience Analysis Sheet

Produce a source-grounded audience analysis for campaign planning and paid acquisition. Preserve a supplied workbook's structure and visual language; otherwise use the compact default schema in `references/audience-framework.md`.

## Required companion skills

- Use the spreadsheet skill for every spreadsheet deliverable. Follow its authoring, rendering, verification, and final-citation requirements.
- Use the PDF skill when source PDFs contain material facts or layout-dependent content.
- Browse official platform documentation when making current claims about ad targeting, audience products, privacy requirements, or feature availability.

## Workflow

### 1. Establish the project truth

Read all user-provided sources before drafting audiences. Extract:

- problem and affected population;
- proposed solution and delivery model;
- urgency and timing;
- unique capability and proof of trust;
- intended change and supporter value;
- geography, language, campaign stage, and conversion goal;
- confirmed rewards, price points, partners, and owned audiences.

Treat source facts as authoritative. Mark unresolved numbers or rewards as missing instead of inventing them. If a linked page is inaccessible, use supplied files and state the limitation; do not bypass access controls.

### 2. Inspect the reference workbook

If the user supplies a workbook, import it and inspect sheet names, used ranges, tables, merged cells, row groups, colors, fonts, borders, widths, heights, wrapping, audience tiers, and wording. Preserve the source file. Create a new output workbook or copy. Match intentional template decisions before applying defaults.

### 3. Build the audience hierarchy

Use three tiers unless the reference prescribes another structure:

1. **Core audiences**: known supporters, participants, partners, creator communities, or local stakeholders most likely to convert first.
2. **Opportunity audiences**: new prospects whose interests, professions, needs, or behaviors connect directly to the problem or solution.
3. **Resonance audiences**: broader groups who may connect through values, memory, place, lifestyle, or adjacent themes.

Give each row one coherent audience. Avoid duplicates differentiated only by wording. Keep the first tier small and high-intent; devote most rows to testable new-customer opportunities when acquisition is the goal.

Read `references/audience-framework.md` before drafting row content.

### 4. Write actionable row content

For every audience, provide:

- **Audience segment**: a concise, recognizable group name.
- **Psychology and behavior**: motivation, context, prior behavior, friction, and evidence threshold.
- **Communication angle**: two to four concrete messages grounded in the project.
- **Reach channels**: owned, earned, partner, community, and paid-media routes.

When the user needs new customers, include all applicable items in the reach-channel cell:

- `興趣測試：` candidate interests to search and test in the current ad manager;
- `相似受眾：` valid seed audiences such as donors, purchasers, registrants, or high-intent visitors;
- `再行銷：` site visitors, video viewers, page engagers, or checkout starters;
- a creative format or partner channel when it materially changes execution.

Do not imply that a proposed interest is currently available. Label interests as test hypotheses and check them in the live platform. Do not target or infer sensitive identity attributes; use contextual interests, geography, opt-in first-party audiences, and creative relevance instead. Use customer lists only when the organization has the necessary rights, permissions, and lawful basis.

### 5. Create the workbook

Default to one focused worksheet with these columns:

1. tier or large category;
2. audience segment;
3. psychology and behavior;
4. communication angle;
5. reach channels, including ad-interest tests when requested.

Preserve template colors and grouped rows. Otherwise use restrained tier colors, wrapped text, readable widths, top-aligned descriptions, centered headers, and distinct category labels. Avoid dashboards, scores, charts, and extra tabs unless they improve a stated decision.

### 6. Verify before delivery

Verify:

- every source claim is supported;
- every audience is meaningfully distinct;
- opportunity rows are suitable for new-customer acquisition;
- each new-customer row has actionable paid or partner reach tactics;
- interest suggestions are hypotheses, not promises of availability;
- sensitive identity is not used as an inferred targeting attribute;
- no row spills beyond the formatted table;
- tables, row groups, colors, wrapping, and widths render correctly;
- the saved workbook has no formula errors or clipped text.

Render and visually inspect the complete output sheet. Reopen or inspect the exported workbook when necessary. Deliver one final workbook unless the user requests variants.

## Output tone

Write in the workbook's language. Prefer specific, human wording over marketing jargon. Describe what motivates the audience and what evidence they need; do not use unsupported demographic stereotypes or generic labels such as “善心人士.”
