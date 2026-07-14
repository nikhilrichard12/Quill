# Littlebird Content Engine -- Gating Policy
Effective: 2026-06-27
Direction: Shahzad (founder)
Rationale: optimizing for SEO/AEO volume. A small amount of uncertainty on integration
capabilities is acceptable (~1-2% error rate). Tier 1 claims carry legal, privacy, or
trust risk; they require no relaxation. Tier 2 integration capabilities may be stated if
telemetry-backed or product-plausible.

---

## TIER 1 -- HARD GATE
Never relax. Always require verification before any claim may be written or published.

Includes:
- Privacy claims (data collection, what Littlebird does/does not see, what is/is not stored)
- Capture mechanism claims (Section 4.4): screenshots, pixels, passwords, incognito windows,
  "if you can't see it, Littlebird can't either"
- Security and encryption claims (AES-256, TLS 1.3, AWS KMS, SOC 2, third-party audits)
- Data storage details (AWS, US East, local vs. cloud, encryption at rest/in transit)
- Legal and compliance claims (SOC 2 certified, GDPR, CCPA, HIPAA if ever added)
- Pricing claims (specific plan names, prices, what is/is not included in Basic vs. paid)
- Customer quotes (Section 14.1 approved only; Section 14.2 requires explicit approval before use)

Writer rule: if a Tier 1 claim is not verified/approved in the Bible, do NOT write it. Insert
[GATED: TIER 1 -- requires verification before publish] and leave a note in the qa-report.

Fact-checker rule: a Tier 1 claim that is not traceable to a verified Bible section is a hard
FAIL. It blocks the page from advancing.

---

## TIER 2 -- SOFT GATE
Integration capabilities only. Applies to what Littlebird reads, writes, finds, or does with
a connected integration (Notion, Gmail, Google Calendar, Todoist, Linear, and all Section 9.x
integrations).

May write if the capability is:
(a) telemetry-backed (appears in usage data or the Bible as SHOWCASE), OR
(b) product-plausible (consistent with how the integration is described in the Bible and does
    not exceed the approved phrasing ceiling)

Do NOT fabricate capabilities with no telemetry or product basis.

Writer rule: write the capability as a clean declarative sentence (no inline [GATED] block).
Do NOT interrupt the page flow with notices for Tier 2 items. In the qa-report, note each
capability that has not yet been app-verified: "CAPABILITY NOTE: [capability] -- telemetry-
backed / product-plausible, not yet app-verified. Confirm before final publish."

Fact-checker rule: do NOT hard-fail a Tier 2 capability claim. Instead, log it as a NOTE
in the factcheck table: "NOTE: capability not yet app-verified -- telemetry/product basis
documented. Not a blocking flag." The overall page verdict may still be PASS.

---

## PUNCTUATION POLICY (ASCII rule clarification)

The Bible bans Unicode em dashes (--) and en dashes (-) from pipeline output. This means:
- BANNED: the Unicode em dash character (--) and en dash character (-)
- ALLOWED: ASCII double-hyphen (--) as a separator (e.g. "ask in Chat -- Littlebird finds it")
- ALLOWED: regular hyphens inside compound words (e.g. "bot-free")

Graders and fact-checkers must NOT flag ASCII double-hyphen "--" as a voice violation.
Only true Unicode em/en dash characters are banned. This resolves a known grader inconsistency.

---

## VERIFICATION LOG -- PROMOTIONS TO PERSONALLY-TESTED TIER

The following integrations have been promoted from TELEMETRY-VERIFIED (Tier 2 soft gate) to
PRODUCT-VERIFIED (personally app-tested) by Nikhil. Once promoted, no eng sign-off gate remains.

| Integration     | Section | Capabilities | Test date  | Result  | Tester |
|-----------------|---------|--------------|------------|---------|--------|
| Notion          | 9.3     | 9 (9R + 0W*) | 2026-06-25 | 9/9 PASS | Nikhil |
| Gmail           | 9.1     | 5 (1R + 2W)  | 2026-06-27 | 5/5 PASS | Nikhil |
| Google Calendar | 9.2     | 2 (1R + 1W)  | 2026-06-27 | 5/5 PASS | Nikhil |
| Todoist         | 9.4     | 11 (6R + 5W) | 2026-06-28 | 11/11 PASS | Nikhil |

* Notion write capabilities (5) were in the original product-verified set; count reflects capabilities in bible.

Todoist note (2026-06-28): Todoist was previously TELEMETRY-VERIFIED under the Tier 2 soft gate.
All 11 capabilities personally tested against a live Todoist account. 11/11 PASS. Promoted to
PRODUCT-VERIFIED. Todoist write capabilities (add-tasks, update-tasks, complete-tasks,
add-projects, reschedule-tasks) are removed from any "pending public-claims sign-off" list.
Telemetry citations in Bible Section 9.4 remain as original evidence basis.

---

## WHAT THIS MEANS FOR EXISTING PAGES

Pages built before 2026-06-27 contain inline [GATED] blocks for integration capabilities.
When those pages are regenerated under this policy, the [GATED] blocks for Tier 2 integration
capabilities are dropped, and the qa-report carries the capability notes instead.

Tier 1 [GATED] blocks remain in any page where the underlying claim is not yet verified.

The VERIFICATION-CHECKLIST.md (output/VERIFICATION-CHECKLIST.md) is unchanged -- verifying
those items remains the goal, it is now simply non-blocking for Tier 2 until publish.
