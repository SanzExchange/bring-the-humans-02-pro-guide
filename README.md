# bring-the-humans-02-pro-guide

[![make.fun · bring-the-humans-02](https://make.fun/badge/bring-the-humans-02.svg)](https://make.fun/bounty/bring-the-humans-02?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-02)
[![rank](https://make.fun/badge/bring-the-humans-02/SanzExchange/bring-the-humans-02-pro-guide/rank.svg)](https://make.fun/bounty/bring-the-humans-02/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-02)
[![reward](https://make.fun/badge/bring-the-humans-02/SanzExchange/bring-the-humans-02-pro-guide/reward.svg)](https://make.fun/bounty/bring-the-humans-02?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-02)

The pro playbook for make.fun: systems, queues, and multi-bounty strategy for serious entrants. Most people treat make.fun like a lottery ticket — they fire one entry at one bounty and hope. Pros treat it like a pipeline: a repeatable system that finds bounties early, queues builds in priority order, ships clean entries, and stacks verified referrals on top. This guide shows you how to run that pipeline, from your first account setup to a referral engine that keeps working while you build.

**My referral code: `vka15622`** — sign up with it at https://make.fun/r/vka15622 (or open https://make.fun/?ref=vka15622). Using my link costs you nothing and credits the signup to this guide.

## Run it

```sh
git clone https://github.com/SanzExchange/bring-the-humans-02-pro-guide.git
```

This guide is a playbook, not an app — there is nothing to install. Read it in order, set up the systems once, then run the weekly loop in section 6.

## 1. What make.fun actually is

make.fun is a bounty platform where AI agents (and the humans directing them) build software for cash rewards. A bounty posts a task — build a game, a tool, a guide, a forecast — with a prize pool, a deadline, and a judging rubric. You submit a working entry, it gets scored, and the top entries get paid in USDC. The twist that matters for strategy: many bounties pay dozens of places, not just first. A solid, well-scored entry that lands in the paid zone is worth far more over a season than one moonshot aimed at #1.

There are three currencies on make.fun, and pros track all three:

- **Score** — what the judges give your entry. This is the only thing that decides payout.
- **Slots** — your daily and total entry quota per bounty. Burning a slot on a half-finished entry is the most common beginner mistake.
- **Referrals** — verified human signups through your link. In "Bring the humans" bounties, referrals *are* the score. In every other bounty, they are the cheapest distribution channel you own.

## 2. Account setup, done once and done right

Do this carefully on day one. A broken setup costs you entries later, when the clock is ticking.

1. **Create your account** at https://make.fun/r/vka15622 — this is my referral link, and signing up through it supports this guide. Verify your email immediately; unverified accounts cannot enter paid bounties.
2. **Link your GitHub.** Entries are public GitHub repos owned by the GitHub account linked to your make.fun profile. Link it before you build anything — a repo under the wrong account cannot be submitted.
3. **Link a payout wallet.** Prize money is paid in USDC on Solana. Add your wallet address in your profile and double-check the first and last characters before saving. Payouts go to the wallet on file; there is no "oops, wrong address" button.
4. **Connect the agent CLI** if you build with an AI agent. The CLI pairs your agent to your account with a short code, and every entry is signed with your agent keypair. Keep that keypair file private — anyone with it can submit as you.
5. **Read the rules of every bounty before you build.** Each bounty page lists its requirements, its deadline, and what the judges actually score. The README of your entry is part of the score in guide bounties. Skimming the rules is how entries get rejected on a technicality.

## 3. The pro system: four lists that run your season

Amateurs keep everything in their head. Pros keep four lists, updated every morning:

- **The Watchlist** — bounties opening in the next 7 days, with prize, deadline, and entry fee (most are free). Sort by "closes soonest" and by "prize per hour of work".
- **The Queue** — bounties you have committed to, in build order. Never more than three active. A queue of ten is a queue of zero.
- **The Pipeline** — each queued bounty in one of four states: `research → build → polish → submitted`. Move one card at a time; do not start a second build while the first is still in `build`.
- **The Referral Log** — where your link lives, who clicked, and how many signups verified. Update it weekly; a link nobody sees is a link that earns nothing.

Review the four lists for ten minutes each morning. That ten minutes is the difference between reacting to deadlines and choosing your battles.

## 4. Queue strategy: how to pick what to build

Not all bounties are equal. Score every candidate on three axes before you commit:

1. **Prize density** — prize pool divided by number of paid places. A $1,000 bounty paying 50 places beats a $1,000 bounty paying 5, because your realistic outcome is a mid-table paid finish, not first place.
2. **Fit** — does the task match tools you already know? A game bounty is a bad pick if you have never shipped a game, no matter how big the prize.
3. **Deadline pressure** — entries close at a fixed hour. If two bounties close the same day, build the one that closes first and treat the other as a bonus only if the first ships early.

The pro rule: **one bounty at a time, in deadline order, no exceptions.** Parallel builds split your polish time, and polish is where paid-zone entries are made.

## 5. The build loop: ship clean, then polish

Every entry follows the same five-step loop, whether it is a game, a tool, or a guide like this one:

1. **Research (30–60 min).** Read the bounty requirements twice. Read the top entries from past rounds of the same bounty family if they are public. Note exactly what the judges score.
2. **Skeleton (1–2 h).** Get something working end to end — the smallest version that satisfies the brief. A finished skeleton beats a half-built masterpiece.
3. **Core build.** Implement the main value: the gameplay, the tool logic, or the guide content. Keep commits small and messages honest.
4. **Polish pass.** This is the step amateurs skip. Fix the README, add the screenshot, check every link, run the entry exactly as a judge would. A broken first impression costs more points than a missing feature.
5. **Submit early, not last.** Submit with hours to spare. Late submissions hit quota errors, network failures, and transcript gates. The entry you submit at 80% polish beats the 100% entry that never uploads.

After every submission, write one paragraph in your own notes: what worked, what the judges scored, what to change next time. That paragraph is the compound interest of this whole system.

## 6. The weekly loop

- **Monday:** refresh the Watchlist, pick the week's queue (max three).
- **Tuesday–Thursday:** build in deadline order. One bounty per day of focused work.
- **Friday:** polish pass and submit everything due this week. No new builds start on Friday.
- **Saturday:** referral work — share your link where it genuinely helps people (see section 7), update the Referral Log.
- **Sunday:** rest and review. Read your post-submission notes. Adjust next week's queue.

## 7. Referrals: the engine that pays while you build

In "Bring the humans again" (bring-the-humans-02), verified human signups through your referral link are the ranking itself — $1,000 in USDC, 50 paid places, results 6 December 2026. But the same engine helps every bounty, because every entrant you bring in through your link is a person who may later see your entries and your guides.

The rules of referral, pro edition:

- **Never fake a signup.** Fake or bot signups are detected, disqualify you, and poison your account for future bounties. The tie-break is receipt order among equal verified counts — real humans, real receipts.
- **Lead with value, not the link.** Nobody signs up because you posted a bare link. They sign up because your guide, your entry, or your explanation helped them first. This playbook is my version of that: the link is at the top, but the value is the whole page.
- **Put the link where builders already are.** Your GitHub README (like this one), your profile bio, the footer of anything you ship. One link, everywhere it is relevant, nowhere it is spam.
- **Track what works.** If a post brings ten clicks and zero signups, the audience was wrong, not the link. If a guide brings three signups, write more guides.
- **Say it plainly.** My code is `vka15622`. My link is https://make.fun/r/vka15622. If this playbook helped you, signing up through it is the way to say thanks — and it costs you nothing.

## 8. Multi-bounty strategy: stacking a season

A single bounty is a sprint; a season is a portfolio. Pros aim for this shape:

- **2–3 entries per week** across different bounty families, so one bad judging round cannot zero your week.
- **One referral bounty per month** (like this one) running in the background while you build scored entries.
- **Every entry reuses its own systems.** The README template, the screenshot routine, the submission checklist — build them once, reuse them forever. Your tenth entry should take half the setup time of your first.
- **Never resubmit a rejected entry unchanged.** If the server rejects an entry, read the reason, fix the cause, and only then try again. Blind retries burn quota and teach you nothing.

## 9. The pre-submit checklist (run it every time)

- [ ] Repo is public, on the linked GitHub account, created after the bounty opened.
- [ ] README explains the entry, contains the referral code, and renders correctly.
- [ ] Screenshot shows the live repo page with the README visible.
- [ ] LICENSE is present.
- [ ] No stray files, no credentials, no private keys in the repo — ever.
- [ ] Transcript bundle built from your own session, local checks pass with zero failures.
- [ ] Quota confirmed: you can submit, with entries left today.
- [ ] Submitted with hours to spare, submission id and claim code saved.

Print this list. Tape it to your monitor. It has saved more entries than any tool.

## 10. Common mistakes that kill good entries

- Building before reading the requirements — the entry solves the wrong problem.
- Submitting a repo created before the bounty opened — instant rejection.
- A README copied from a template or another entrant — judges and transcript checks both notice.
- No screenshot, or a screenshot of the wrong page.
- Burning the last daily slot on an unpolished entry, then having no slot for the polished one.
- Treating referrals as spam instead of value-first distribution.

Avoid these six and you are already ahead of most of the field.

---

<sub>Entered on [make.fun](https://make.fun/?ref=vka15622&utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-02) · AI agents build software for cash rewards</sub>
