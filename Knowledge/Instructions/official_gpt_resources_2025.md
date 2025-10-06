# Official Custom GPT Documentation Index (October 2025 refresh)

This index consolidates the most up-to-date official help center and platform documentation from OpenAI about creating, managing, and publishing custom GPTs. It is intended to supplement CGW's guidance so builders can jump straight to authoritative instructions when they need deeper detail or policy clarifications.

> **Note:** All of the articles below live inside OpenAI's dedicated [GPTs help center collection](https://help.openai.com/en/collections/9139824-gpts). Individual article slugs are provided for quick access.

| Topic | Official resource | Key takeaways for builders | How CGW users can apply it |
| --- | --- | --- | --- |
| Getting started | [Create a GPT](https://help.openai.com/en/articles/8820655-create-a-gpt) | Walks through the updated builder interface, including how instructions, Knowledge files, conversation starters, and capability toggles (web browsing, DALL·E, code interpreter) now appear in the side-by-side preview experience. | Pair this with CGW's EGBA walkthroughs to mirror the official builder flow and verify nothing in the UI has changed before sharing directions with teammates or clients. |
| Day-to-day management | [Manage GPTs](https://help.openai.com/en/articles/8820614-manage-gpts) | Covers renaming, duplicating, archiving, setting default capabilities, and controlling whether a GPT is visible only to you, shared by link, or listed publicly. | Use these controls to keep draft GPTs private until they are ready for user testing, and document the lifecycle inside CGW's project notes. |
| Privacy and data controls | [Custom GPT privacy controls](https://help.openai.com/en/articles/8595947-custom-gpt-privacy-controls) | Explains the "Allow my GPT to be used for model improvement" toggle, data retention behavior, and how Knowledge files are stored. | Aligns with CGW's emphasis on ethical builds—reference this when advising on compliance or responding to user privacy questions. |
| GPT Store overview | [GPT Store overview](https://help.openai.com/en/articles/8939316-gpt-store-overview) | Details eligibility (Plus/Team/Enterprise), quality and policy review, how rankings work, and the new revenue share metrics dashboard. | Reference before you encourage someone to publish via CGW so they can prepare assets, confirm policy alignment, and understand discovery mechanics. |
| Builder profile | [Set up your builder profile](https://help.openai.com/en/articles/8939335-set-up-your-builder-profile) | Explains display name, profile handle, tagline, and external links required for public listings plus how verification works. | Include these requirements in CGW project kickoff checklists so marketing assets are ready before submission. |
| Publishing workflow | [Publish or share a GPT](https://help.openai.com/en/articles/8820616-publish-or-share-a-gpt) | Step-by-step instructions for sharing via direct link, publishing to the store, and updating version notes. | Sync this with CGW's slash commands (/MAKE, /BUILD) to outline next steps once a configuration is approved. |
| GPT actions | [GPT actions quickstart](https://platform.openai.com/docs/guides/gpt-actions) | Provides the modern schema format, authentication models (API key, OAuth), testing inside the builder, and deployment safeguards. | When CGW suggests adding actions, crosslink to this quickstart so developers can wire up external tools confidently. |
| Analytics | [GPT analytics dashboard](https://help.openai.com/en/articles/8940147-gpt-analytics-dashboard) | Describes engagement metrics (opens, conversations, saves), trending tabs, and filters for time ranges. | Use analytics data to inform CGW-led iteration cycles and highlight measurable outcomes to stakeholders. |
| Workspace roles & compliance | Workspace roles and permissions *(see GPTs help center)* | Breaks down admin, builder, and analyst permissions, audit log availability, and how Workspace-wide publishing works. | Map CGW recommendations to the right approvers and keep governance artifacts aligned with Workspace controls. |
| Policy compliance | [GPT policy and review guidelines](https://help.openai.com/en/articles/8859858-gpt-policy-and-review-guidelines) | Summarizes restricted content, intellectual property expectations, and enforcement steps reviewers take before a GPT appears in the store. | Reference this whenever CGW warns about sensitive content so builders can remediate issues before submission. |

## How to keep this index current

1. Revisit the GPTs collection link at least once per release cycle—OpenAI adds new articles as capabilities expand (e.g., workspace analytics, fine-grained access controls).
2. Compare article timestamps with CGW's change log; add new rows or update summaries when OpenAI revises the builder UI.
3. If an article is deprecated, move it to an "Archive" subsection and note the replacement resource so historical instructions remain traceable.
4. Encourage contributors to open issues or PRs whenever they notice help center updates during their own GPT building work.

## Emerging documentation to watch

- **Workspace governance** – Articles covering Workspace roles, audit logs, and credential management continue to expand; monitor them to keep the compliance row above accurate.
- **GPT Store monetization** – New guidance on regional availability, payout dashboards, and promotional programs is expected as the Store matures.
- **Analytics exports** – Keep an eye out for documentation describing webhook or CSV exports so CGW workflows can incorporate automated reporting.
