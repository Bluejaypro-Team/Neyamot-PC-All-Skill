---
name: slack-nap-site-auditor
description: >
  Audit site NAP (Name, Address, Phone) consistency, Local SEO citations, and site structures,
  with automated Slack notifications and reporting pipeline.
---

# Skill: Slack NAP & Site Auditor

Automated Local SEO Name, Address, Phone (NAP) consistency auditor and website structure inspector with integrated Slack notification capabilities.

## Key Capabilities

1. **NAP Consistency Audit**: Verify business Name, Address, and Phone number uniformity across website footers, contact pages, header schemas, and local citations.
2. **Local Schema Inspection**: Analyze `LocalBusiness` and `Organization` JSON-LD schema markup for geo-accuracy.
3. **Slack Reporting Integration**: Dispatch real-time audit summaries, citation discrepancies, and UX friction findings to configured Slack channels.

## Execution Workflow

1. **Target Verification**: Inspect target domain header/footer NAP metadata and schema markup.
2. **Discrepancy Detection**: Identify phone number variations, address mismatches, and canonical inconsistencies.
3. **Slack Dispatch**: Format findings into markdown reports and send notifications to designated Slack channels via Slack API / Webhooks.
