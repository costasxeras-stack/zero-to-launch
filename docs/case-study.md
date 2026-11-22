# Case study: Zero to Launch

## The question

Most PM case studies show one stage well and skip the rest. I wanted one idea taken through every stage: discover, define, ideate, prototype, test and launch, with each claim marked as confirmed, proxy or hypothesis. The idea comes from my own work: Spend Lens covers one person's spending, and couples who share some money and keep some separate are the obvious next problem.

## Approach

I started from the evidence I already had (Spend Lens and the review proxy), wrote the job to be done and principles, compared three solutions and listed the riskiest assumptions. I built the smallest prototype that tests those assumptions and wrote the test and launch plans before building more.

## Findings

### 1. Partners are a common theme in money app reviews (proxy)

27 of 45 App Store reviews in Listening Tour mention a partner.

### 2. Splitting is where ratings drop (proxy)

Splitting and who owes whom averaged 2.93 stars in the same sample, the lowest among common themes. This shaped the choice of a fair-share rule instead of a running debt.

### 3. Partly-sharing couples are underserved (hypothesis)

Not tested yet. Interviews and a two-week prototype test are planned.

## Decisions

### A fair-share rule instead of a running debt

Split apps frame a partner as a debtor, and splitting had the lowest ratings in the review proxy.

**Decision:** Show each partner's share against an agreed rule (50/50 or by income) and phrase gaps without blame.

Full record: [decisions/0001-fair-share-not-debt.md](decisions/0001-fair-share-not-debt.md)

### Personal payments are hidden from the partner

Joint-account apps show everything. Some couples keep money personal on purpose.

**Decision:** Payments are shared or personal. The partner sees personal payments only as "personal", without place or amount.

Full record: [decisions/0002-personal-is-private.md](decisions/0002-personal-is-private.md)

### Launch inside Spend Lens, not as a new app

A new app needs its own import, categories and trust.

**Decision:** Build Our Money as a shared space in Spend Lens and sequence it after transfer matching and split payments.

Full record: [decisions/0003-feature-not-app.md](decisions/0003-feature-not-app.md)

## What I learned as a PM

- Marking evidence by type at every stage keeps a case study honest
- Copy is product in money apps: the same number can sound fair or accusing
- Choosing to launch inside an existing product is a strategy decision, not just an engineering one

## Limits

- No interviews or user tests yet
- Prototype runs on one device
- Sample data only

## What I would do next

1. Run five interviews with Listening Tour and update Discover
2. Run the two-week prototype test with [5] couples
3. Build encrypted export and import between partners

## My role

I framed the problem, made the product calls, checked every number and wrote the conclusions. 
