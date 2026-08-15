# Account Expansion

**A structured AI skill for expanding existing customer accounts.**

Account Expansion is a free AI-guided interrogation framework for AEs, AMs, CSMs, founders, and sales leaders who need to decide whether an existing customer account is ready for more revenue, and if so, how to pursue it without damaging the relationship.

This is not Greenfield. Greenfield is for breaking into accounts where no relationship exists. Account Expansion starts from the existing relationship, current product footprint, adoption health, commercial history, stakeholder map, and customer trust level.

[greenfield.tools/account-expansion](https://greenfield.tools/account-expansion)

---

## What it does

Account Expansion walks the seller through a structured expansion planning process:

1. **Account Identity And Relationship Baseline** - locks the exact customer, current products, account owner, hypothesis, CSM coverage, and internal motion ownership.
2. **Expansion Trigger Radar** - identifies time-based, usage-based, milestone-based, corporate, and internal triggers.
3. **Segmentation And Whitespace Heatmap** - classifies account tier and maps green, yellow, red, and grey zones across teams or business units.
4. **Commercial Baseline** - maps contract value, SKUs, renewal timing, procurement path, and previous expansion history.
5. **Product Footprint And Adoption** - evaluates current usage, value realization, post-onboarding milestones, and CSM readiness.
6. **Relationship History And Account Sentiment** - captures relationship highs, lows, advocacy, escalations, and referenceability.
7. **Stakeholder Map And Champion Strength** - scores champion strength, executive awareness, blockers, and relationship warmth.
8. **Business Priorities And Expansion Narratives** - connects expansion plays to customer priorities instead of quota.
9. **Whitespace, Products, SKUs, And Dollar Bands** - sizes upsell, cross-sell, and add-on plays with confidence and timeline.
10. **Risk Register And Product Gaps** - surfaces support issues, adoption gaps, competitor threats, product gaps, and bandwidth constraints.
11. **Enablement, Executive Alignment, Advocacy, And Events** - identifies earn-the-right actions before asking for more.
12. **Expansion Brief** - produces the final strategy, scorecard, 30-60-90 plan, and one-week focus sheet.

---

## The core gate

The skill asks whether the account has earned an active expansion ask yet.

Expansion is only `READY` when:

- value realization is strong enough
- champion strength is sufficient
- timing is real or a documented trigger exists
- critical risks have owners and mitigation plans
- customer success endorses readiness, or the lack of CSM input is called out as a gap
- the customer has bandwidth to absorb more product

If the account is not ready, the skill says so and pivots to enablement, trust repair, adoption, or multi-threading.

---

## Final output

The final artifact is an **Expansion Brief** with:

- account snapshot
- timing window
- commercial baseline
- product footprint and value assessment
- relationship health
- stakeholder map
- expansion narratives
- whitespace plays
- risks and gaps
- enablement and success plan
- advocacy and executive plan
- 30-60-90 expansion plan
- one-week focus sheet
- scorecard
- intelligence gaps
- machine-readable run status

---

## How to use

1. Copy the contents of [`SKILL.md`](./SKILL.md).
2. Paste it into Claude, ChatGPT, Gemini, Codex, Cursor, Claude Code, Gemini CLI, or another capable AI tool.
3. Say: `Run Account Expansion on [Company Name]`.
4. Answer one question at a time.
5. Receive an Expansion Brief if the account has enough context to complete the run.

No login. No paywall.

---

## When to use this vs the other Greenfield skills

- **Greenfield**: use when you are breaking into a cold account and need research, warm paths, executive routing, and an Account Brief.
- **Account Expansion**: use when the account is already a customer and you need to decide whether expansion is earned.
- **Executive Briefing**: use when you are selling or planning an executive briefing, executive meeting, or executive demo.
- **POV**: use when you already have a signal or account brief and need a financially grounded angle, business case, or internal approval narrative.
- **QBR**: use when you need an internal sales QBR, customer QBR, EBR, renewal review, value review, pipeline review, or next-quarter action plan.

They work together. Greenfield finds the new-logo wedge. Account Expansion finds the install-base growth path. Executive Briefing builds the meeting strategy. QBR turns quarter performance or customer value into a review-ready plan. POV sharpens the narrative.

---

## What's in the repo

```text
account-expansion/
├── SKILL.md              The skill itself
├── ACCOUNT_EXPANSION.md  Copy-friendly canonical markdown
├── README.md             Project overview
├── LICENSE               MIT license
└── agents/openai.yaml    Skill metadata
```

---

## Built by

[Mangosteen Studio](https://mangosteen.studio) - AI tooling for account executives, by an account executive.

Part of the Greenfield suite: [greenfield.tools](https://greenfield.tools)

---

## License

MIT. Use it, modify it, fork it, ship it.
