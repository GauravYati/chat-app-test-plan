# Chat Application — Test Plan & Test Cases

Test plan and IEEE 829-style test cases for the Chat Application across Web, Android, and iOS.

## Scope
In scope: text messaging, attachments, media, documents, previews, message actions, chat/contact actions, status/presence, discovery, compatibility, security, performance, accessibility.

Out of scope: end-to-end encryption, third-party YouTube API behavior beyond link preview.

## Repository layout
- `docs/` — test plan, strategy, environment, risks, entry/exit criteria, defect management
- `test-cases/` — test cases grouped by feature area
- `traceability/` — feature-to-test-case traceability matrix
- `test-data/` — test data notes and placeholders
- `templates/` — defect, execution, and summary report templates
- `test-cases.csv` — importable test case backlog for GitHub Projects

## Test case conventions
- ID: `TC-<GROUP>-<NNN>` where GROUP = MSG, ATT, ACT, CHT, STA, DSC, XCT
- Priority: P1 = Critical, P2 = High, P3 = Medium, P4 = Low
- Type: F = Functional, N = Negative, B = Boundary, UI = User Interface, C = Compatibility, S = Security, P = Performance, A = Accessibility

## Global precondition
Two test users — User A (sender) and User B (receiver) — are logged in on separate sessions with an active 1-to-1 chat. Test data files are preloaded.

## How to use
1. Import `test-cases.csv` into GitHub Projects.
2. Create labels and milestones.
3. Execute test cases and log defects using the issue template.
4. Update execution status and traceability.

## Status
Draft — ready for review and execution.
