# Primary App

## Responsibility
Main runtime for `portfolio`.

## Dependencies
- HTML
- CSS
- JavaScript
- jQuery
- Bootstrap

## Inbound APIs
- No formal inbound API is visible.

## Outbound APIs
- No confirmed external provider or downstream API.

## Databases Used
- No dedicated database visible.

## Queues / Topics
- No queue/topic layer visible.

## Critical Workflows
- Single-page portfolio with hero section, about section, project gallery, and contact section
- Project cards that summarize and link out to multiple GitHub repositories
- Skill progress bars covering front-end, JavaScript, design, and database tools
- Resume download call-to-action and hiring-oriented contact prompts
- Bootstrap and jQuery-based interactions with a custom visual theme

## Failure Modes
- There is no strong operational harness here; expect manual verification and thinner safety rails before changing behavior.

## Scaling Concerns
- current implementation appears intentionally lightweight
- there is no evidence of multi-service scaling machinery unless repo docs add it

## Operational Concerns
- start from repo-local `.claude/` docs and Graphify summary before code changes
- validate environment assumptions before debugging logic

## Important Source Files
- `Index.html`
- `_scripts/script.js`
- `_styles/styles.css`
- `README.md`
- `README.MD`

## Dangerous Code Paths
- There is no strong operational harness here; expect manual verification and thinner safety rails before changing behavior.

## Testing Strategy
- No standardized automated test command is visible.

## Known Technical Debt
- Pending work is unknown from current repo docs.
