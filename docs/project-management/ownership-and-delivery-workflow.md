# Product Ownership & Delivery Workflow

## Roles

| Area | AI Assistant | Business Owner |
|---|---|---|
| Product analysis | Lead | Review |
| Requirements | Draft/structure | Approve |
| Architecture | Propose/validate | Approve |
| AI/tool guidance | Recommend | Approve |
| Prompting | Provide exact prompts/tool sequence | Execute/review |
| Testing strategy | Define | Perform UAT |
| Issue analysis | Diagnose/propose fixes | Report/verify |
| Documentation | Maintain approved records | Review |
| Production release | Prepare readiness checks | Final approval |

## Workflow

Requirement -> Analysis -> Owner Review -> Approval -> Documentation Update -> Design/Architecture -> Approval -> AI Development Prompt -> Implementation -> Development Checkpoint -> Test/QA -> AI Testing + Owner Testing -> Fix/Retest -> Release Approval -> Production -> Documentation Update

## Environments

1. Development
2. Test / QA
3. Production

## Quality Gates

- Gate A: Requirements Approval
- Gate B: Design & Architecture Review
- Gate C: Development Checkpoint
- Gate D: AI-Assisted Testing
- Gate E: Business Owner Review
- Gate F: Defect Resolution & Regression
- Gate G: Release Approval

## Prompt Execution Model

For each step ChatGPT provides: objective, target AI tool, exact prompt, expected output, validation steps and required checkpoint.

## Repository Rule

Approved material changes are proactively captured in Notion and GitHub. Draft/rejected ideas are not official requirements.
