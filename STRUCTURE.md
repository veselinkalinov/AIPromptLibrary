# Repository Structure

The library uses numbered, topic-based directories so prompts remain predictable as the collection grows.

## Taxonomy

| Directory | Category | Scope |
|---|---|---|
| `01-mega-prompts/` | Mega Prompts | Session protocols and high-rigor reasoning prompts. |
| `02-learning-system/` | Learning System | Reusable learning workflows, study-plan generators, and NotebookLM prompts. |
| `03-prompt-engineering/` | Prompt Engineering | Prompt optimization, model selection, and meta-prompting. |
| `04-finance-investing/` | Finance & Investing | Investment research, portfolio planning, fundraising, and financial education. |
| `05-design-ui-ux/` | Design & UI/UX | Brand, product design, accessibility, Figma, and design-system workflows. |
| `06-business-marketing/` | Business & Marketing | Growth, sales, brand, social media, and go-to-market prompts. |
| `07-health-fitness/` | Health & Fitness | Training, nutrition, wellness, and health-learning prompts. |
| `08-personal-productivity/` | Personal Productivity | Planning, personal development, and assistant workflows. |
| `09-education-courses/` | Education & Courses | Course creation, curricula, guides, and training programs. |
| `10-templates-generic/` | Generic & Lifestyle Templates | Broad reusable templates and lifestyle exploration prompts. |
| `11-writing-content/` | Writing & Content | Books, scripts, presentations, and creative content production. |
| `12-professional-operations/` | Professional Operations | Project, administrative, audit, and workplace operations. |
| `13-technology-research/` | Technology & Research | AI systems, technical evaluation, and research-oriented prompts. |

## Prompt file format

Each prompt uses one Markdown file with:

1. A descriptive H1 title.
2. Model, rating, and use-case metadata when available.
3. A source link for Notion-synchronized prompts.
4. A divider followed by the copy-ready prompt text.

## Naming rules

- Use lowercase kebab-case filenames.
- Keep one prompt per file unless the prompt is intentionally bilingual.
- Add `-notion` only when a Notion prompt has the same title as an existing curated prompt but different text.
- Add a numeric suffix only when separate prompts share the same title.
- Never overwrite a curated prompt during synchronization; compare normalized prompt text first.

## Synchronization rules

- Treat the Notion database as an upstream source, not a destructive mirror.
- Skip blank database rows.
- Match by normalized prompt text before title.
- Preserve repository-only prompts and all existing files.
- Update `CATALOG.md` and category counts whenever prompts are added.

