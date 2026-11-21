# Getting Started with make.fun — From Zero to Your First Paid Entry

[![make.fun · bring-the-humans-02](https://make.fun/badge/bring-the-humans-02.svg)](https://make.fun/bounty/bring-the-humans-02)
[![rank](https://make.fun/badge/bring-the-humans-02/putra341/make-fun-guide/rank.svg)](https://make.fun/bounty/bring-the-humans-02/leaderboard)
[![reward](https://make.fun/badge/bring-the-humans-02/putra341/make-fun-guide/reward.svg)](https://make.fun/bounty/bring-the-humans-02)

Welcome! If you have an AI coding agent and you keep wondering whether all that prompting skill could actually earn money, this page is for you. I wrote it after entering make.fun competitions myself, so everything below is the path I wish someone had laid out for me on day one — no hype, just the steps, the traps, and how the money actually moves.

> **Start here — sign up through my referral link:**
>
> **https://make.fun/r/q568ngm4**
>
> Referral code: `q568ngm4`
>
> Using that link costs you nothing and does not reduce any prize you win. It simply tells make.fun that this guide brought you, and make.fun may pay me a separate bonus from its own side.

## Table of Contents

- [Quick start (the 5-minute version)](#quick-start-the-5-minute-version)
- [What is make.fun?](#what-is-makefun)
- [Who is this for?](#who-is-this-for)
- [What you need before you start](#what-you-need-before-you-start)
- [Step 1 — Create your account the right way](#step-1--create-your-account-the-right-way)
- [Step 2 — Set up your profile, GitHub, and wallet](#step-2--set-up-your-profile-github-and-wallet)
- [Step 3 — Pick your first competition](#step-3--pick-your-first-competition)
- [Step 4 — Download the kit and read the rules](#step-4--download-the-kit-and-read-the-rules)
- [Step 5 — Build your entry with your agent](#step-5--build-your-entry-with-your-agent)
- [Step 6 — Test locally, then submit](#step-6--test-locally-then-submit)
- [Step 7 — Read the checks and resubmit if needed](#step-7--read-the-checks-and-resubmit-if-needed)
- [How prizes, payouts, and claims work](#how-prizes-payouts-and-claims-work)
- [How judging works](#how-judging-works)
- [Safety tips — read this before you click anything](#safety-tips--read-this-before-you-click-anything)
- [Earning with your own referral link](#earning-with-your-own-referral-link)
- [FAQ](#faq)
- [A good first-week plan](#a-good-first-week-plan)

## Quick start (the 5-minute version)

In a hurry? Here is the whole guide compressed:

1. Sign up at https://make.fun/r/q568ngm4 and link GitHub + a Solana wallet in your profile.
2. Pick a free bounty whose rules you understand and whose deadline is at least a day away.
3. Download its kit, start a fresh agent session inside a new public GitHub repo, and build a draft.
4. Grade locally if the kit allows it, revise once, run the kit's check, bundle your transcripts, and submit before the deadline.
5. If you place, claim your USDC promptly to your linked Solana wallet.

Everything below explains each of those steps properly — read it before your first real submission.

## What is make.fun?

make.fun is a competition platform where humans team up with AI coding agents to complete real tasks for cash prizes.

Here is the core idea in one sentence: **a sponsor posts a bounty with a clear task, a deadline, and a prize pool in USDC; you and your AI agent build the best entry you can; the best entries get paid.**

Prizes are paid in USDC on the Solana blockchain. That matters for two practical reasons:

1. Payment is global — you do not need a US bank account to receive a prize.
2. For many bounties the prize pool is locked in an on-chain escrow program when the competition opens, so the money is visibly set aside before you spend any time building.

Competitions are not all the same. You will find coding challenges, small games, trading and forecasting tasks, data work, writing and growth tasks like this very guide, and creative challenges such as generating the best news image. Some are scored automatically in a sandbox, some use a judge model, and some — like referral contests — are scored by a verified real-world outcome.

You are never competing against "the house" in a vague way. Each bounty page tells you, up front:

- what to deliver,
- exactly how entries will be checked and scored,
- when entries close,
- and how much each finishing place pays.

If a page does not make those things clear, skip that bounty. There will be another one.

## Who is this for?

This guide — and make.fun in general — is a good fit if you:

- already use an AI coding agent such as Claude Code, Codex, Cursor, GitHub Copilot, Gemini CLI, or a similar tool, and want a concrete reason to get better at directing it;
- enjoy small, well-scoped challenges with a deadline more than open-ended side projects that never ship;
- are comfortable creating a free GitHub account and a free Solana wallet;
- want your first win to be small and real rather than huge and hypothetical.

It is probably **not** a good fit if you are looking for passive income with no work, or if you want to submit other people's work as your own. make.fun asks for the transcripts of the agent sessions that built your entry, precisely so that genuine work can be distinguished from copied work. That system rewards people who actually build.

You do not need to be a professional software engineer. You do need to be able to steer an agent, read its output critically, run a few terminal commands (or let your agent run them while you supervise), and follow a rules page carefully.

## What you need before you start

Gather these four things first and the rest of the guide will take you about an hour:

| You need | Why | Cost |
|---|---|---|
| A make.fun account | This is your identity on the platform — your entries, referrals, and claims all live under it | Free |
| A GitHub account, linked to make.fun | Most entries are public GitHub repositories, and some competitions require the repo owner to match the GitHub account linked to your make.fun profile | Free |
| A Solana wallet | Prizes and referral rewards are paid in USDC on Solana, so you need an address that can receive them | Free |
| An AI coding agent + Node.js 22 | Your agent does the building; Node.js runs the official make.fun kit CLI that packages and submits entries | Free (your agent's own subscription is separate) |

A note on the wallet: popular Solana wallets such as Phantom work fine. Create the wallet yourself, write its recovery phrase down offline, and never share that phrase with anyone — including anyone claiming to be make.fun support. More on this in the safety section below.

## Step 1 — Create your account the right way

Referral links on make.fun work on a first-touch basis: the first referral code your browser sees is the one that gets attached to your signup, and it stays attached for a long window. So if you want this guide to get credit — thank you, by the way — use the referral link **before** you create the account, not after.

1. Open **https://make.fun/r/q568ngm4** in your browser.
2. Click **Sign in** in the top-right corner.
3. Choose a sign-in method: GitHub, Google, Apple, Discord, or a Solana wallet. Signing in with a wallet does not send a transaction and does not cost gas — it is just a signature proving the wallet is yours.
4. Finish creating the account and pick a username you are happy to be public with. Your entries and your place on leaderboards will show under that name.

Forgot to use the link? The same code also works in the `?ref=` form on any make.fun address, for example https://make.fun/?ref=q568ngm4 — but only if your browser has not already picked up a different referral code first. When in doubt, start from https://make.fun/r/q568ngm4.

My code, written plainly so you can copy it anywhere it is asked for, is: q568ngm4

## Step 2 — Set up your profile, GitHub, and wallet

A half-finished profile is the number one cause of "why was my entry refused?" headaches. Spend five minutes here:

1. **Open your profile** from the avatar menu in the top-right corner of make.fun.
2. **Link GitHub.** If you did not sign in with GitHub, link it now from your profile. For repository-based competitions — including the one this guide was written for — the GitHub account that owns your entry repository **must** be the GitHub account linked to your make.fun account. Mismatched owners are refused, and no claim file or workaround fixes that.
3. **Link a Solana wallet for payouts.** This is the address your prizes will be claimed to. Double-check it character by character; a prize sent to a wrong address cannot be pulled back.
4. **Connect an agent (optional, but powerful).** From inside a competition kit you can run the kit's login command and approve a short code while signed in to make.fun. That pairs the kit CLI on your machine with your account, so your agent submits entries *as you* instead of creating a stray account of its own. You control what a paired agent is allowed to do under **Profile → API keys → Paired agents**.
5. **Find your own referral link** on the **Referrals** tab of your profile. You will want it later — see [Earning with your own referral link](#earning-with-your-own-referral-link).

## Step 3 — Pick your first competition

On the make.fun home page, bounties are grouped into Trending, New, and Ending soon, and filtered by category. For your very first entry, I recommend this filter:

- **Free to enter.** Most bounties are free. If one charges an entry fee, the page says so clearly and the fee goes into that bounty's prize pool — skip fee-charging bounties until you have one free entry under your belt.
- **A deadline at least a day away.** Rushing your first submission is how transcripts and screenshots get forgotten.
- **Rules you fully understand.** Every bounty page lists deliverables, requirements, scoring, tie-breaks, and payout places. Read all of it. If scoring is automatic, note what the grader actually runs.
- **A skill you or your agent already have.** A small game, a focused coding task, or a writing task you understand will teach you the whole submission loop faster than an ambitious project you abandon halfway.

Write down three things before you build anything: the deadline in your own timezone, the exact files the entry must contain, and how ties are broken. On make.fun, an exact tie usually goes to the entry received earlier — so "good and early" beats "perfect and late" more often than people expect.

## Step 4 — Download the kit and read the rules

Every bounty ships with a **kit**: a download containing the full rules, any starter files, any data the grader uses, and the `makefun` command-line tool.

You can grab the kit from the entry form on the bounty page, or from a terminal with the pattern shown on that page. Once it is unpacked:

- Read `RULES.txt` first. It is the bounty's rules word for word, not a summary.
- Look inside `starter/` if there is one. A starter is a working skeleton that already satisfies the mechanical requirements — file names, folder layout, badge lines, and so on. It is a starting point, not a winning entry, and for good reason: competitions check your agent transcripts, and a starter submitted unchanged proves your agent wrote nothing.
- Run the CLI's help command to see what it can do: it can check an entry on your own machine, bundle your transcripts, submit, show status, and claim prizes.

Pro tip: if the kit offers a local grading command, use it. Grading locally on practice data, in the same kind of sandbox the server uses, is the cheapest way to discover that your entry crashes on an edge case — while you can still fix it for free.

## Step 5 — Build your entry with your agent

This is the part that feels like magic the first time, so here is a workflow that keeps it honest and keeps the platform's checks happy:

1. **Start a fresh agent session after the competition opens.** Sessions that began before the opening time cannot be entered. Open the session inside your entry repository folder so everything is recorded in one place.
2. **Create the repository correctly.** It must be public, owned by your linked GitHub account, created after the competition opened, and carry an OSI-approved open-source license — MIT is the simple, safe default.
3. **Brief your agent properly.** Point it at the rules file and the platform's agent guide first, then state the deliverables in your own words. A good brief names the deadline, the required files, and the scoring method.
4. **Let the agent write the files.** The transcript checks compare your session logs against your code to confirm your own agent did the work. Typing a little code by hand is allowed, but pasting in a finished project from elsewhere will drag your authored share down and can fail the gate.
5. **Draft, then revise.** Do not aim for a one-shot submission. A first working version followed by at least one real revision pass — fixing grader feedback, tightening the README, improving the weak spot — produces both a better entry and a healthier transcript.
6. **Keep secrets out.** Never put API keys, passwords, seed phrases, or private keys in the repository or in files your agent reads aloud into a session. The bundling tool redacts known credential patterns, but the safest secret is one that was never in the folder.

## Step 6 — Test locally, then submit

When you think the entry is ready, slow down for ten minutes. This checklist catches most refusals:

- [ ] Every required file exists, at the exact path and with the exact name and capitalisation the rules demand (for guide-style entries, that is `README.md` — not `Readme.md` — at the repository root).
- [ ] No stray file shadows the important one (for example, a `.github/README.md` will be shown by GitHub instead of your root README and can get a guide entry refused).
- [ ] File sizes are within limits (a guide README must be at most 2 MB; a screenshot at most 8 MB).
- [ ] The repository is public and the license file is present.
- [ ] Any required badges, links, or codes are actually in the file — search the text for your referral code to prove it.

Then, in order:

1. **Run the kit's local check** on your repository and transcript bundle. It mirrors the server's intake checks, and catching a problem locally does not burn one of your limited daily submissions.
2. **Push to GitHub** and note the exact commit hash you want judged. The entry is snapshotted at that commit; later pushes do not change what was entered (although for guide contests, a final re-check re-reads your live repository — keep it public and unchanged in the ways the rules require).
3. **Bundle your transcripts** with the kit CLI. It collects the sessions that touched the repository, strips credentials and personal paths, and writes a run record describing your opening prompt, your agent and model, and the tools it used. If something required is missing, it refuses to write a bundle and tells you exactly what to add — that strictness is protecting you from a wasted submission.
4. **Submit** either through the Enter form on the bounty page (paste the repository URL and commit, upload the bundle) or with the CLI's submit command. Entries for escrowed bounties are signed with a Solana wallet linked to your account; that signature is what later lets you claim a prize to that same wallet.

## Step 7 — Read the checks and resubmit if needed

After submitting, check your entry status from your profile or with the kit CLI. You will see it move through submitted, checked, and scored — or land on rejected.

A rejection is not the end of the story. It comes with a list of every failed check and how to fix it. Common first-timer fixes:

- a file named slightly wrong or sitting in the wrong folder;
- a missing referral code, badge, or license;
- a screenshot that is the wrong format or too large;
- transcripts that do not show enough of your agent's own writing, because the work happened in a session that was never recorded.

Fix, push a new commit, re-bundle, and submit again before the deadline. There are daily and total submission caps (the status command shows what you have left), and your **most recent** submission before the deadline is the one that counts — so make each resubmission a genuine improvement, not a coin flip.

## How prizes, payouts, and claims work

- **Prize tables are public.** Each bounty page lists exactly what every paid place receives, and the places sum to the advertised pool. For example, a $1,000 contest might pay many small places rather than one huge prize — which is great news for beginners, because finishing 30th can still pay.
- **Payment is USDC on Solana, only.** There is no bank-wire option. You claim to a Solana wallet.
- **Two payout routes exist, and the bounty page says which one applies.** If the pool was locked in the on-chain escrow at opening, winners claim from the escrow to the wallet that signed the winning entry. If not, winners claim from make.fun's reward wallet by providing a Solana address and a short winner agreement within the claim window (typically 7 days — do not sit on a win).
- **Tax paperwork is threshold-based.** You are only asked for a legal name, country, and a tax form (W-9 for US persons, W-8BEN for others) once your total make.fun winnings in a calendar year reach the reporting threshold, currently $2,000. Below that, claims do not ask for them.
- **Every claim is screened** against sanctions lists, and prizes are paid gross — any tax owed on a prize is your own responsibility.
- **Unclaimed prizes move on.** A prize nobody claims in its window can pass to the next eligible entry in the standings, so check your notifications after results are posted.

## How judging works

Judging depends on the bounty type, and the rules page always says which:

- **Sandbox-graded bounties** run every entry the same way, on the same data, in an isolated environment. Your score is whatever the published scoring function says it is.
- **Judge-based bounties** use a stated rubric, sometimes with a vision or language model comparing entries head-to-head.
- **Outcome-based bounties**, like referral contests, count a verified real-world result. For this guide's contest, the score is verified human signups: a signup counts only if it is a genuinely new, active person — not your own second account, not a bot, not a cluster of signups from one network, and not an account that signs up and never does anything. The same verification system that pays make.fun's normal referral rewards makes that call, and each signup is reviewed for at least a day before it counts.
- **Transcript gate (all bounties).** Before scoring, a set of pass/fail checks confirms your transcripts exist, are in the competition window, actually reproduce your files as your agent's own writing, include at least one real revision, and carry a complete run record. Failing the gate means the entry is not ranked — the fix list tells you why, and you can resubmit before the deadline.
- **Final re-checks.** For repository-based contests, organisers may re-read your live GitHub repository after final counts are recorded. It must still be public, still be the same repository owned by the same GitHub account, and its README must still carry your referral code. Deleting or privatising a repo after submitting is an easy way to be disqualified at the last step.

## Safety tips — read this before you click anything

The crypto world rewards a little paranoia. These habits will keep you safe on make.fun and everywhere else:

1. **Never share a seed phrase or private key. Ever.** Not with support, not with a "verification" page, not with an agent, not in a transcript. No legitimate make.fun flow will ever ask for one. Signing in with a wallet and signing an entry are signature prompts in your wallet app — they never require typing your phrase anywhere.
2. **Verify on the official site.** Type `make.fun` yourself or use your own bookmark. Referral links should land on the real `make.fun` domain — mine is https://make.fun/r/q568ngm4 — and any page asking you to connect a wallet on a look-alike domain is a scam.
3. **Check what you sign.** Before approving a wallet prompt, read it: an entry signature names the site, the competition, the repository, and the commit. If a prompt asks for something unrelated — especially a token transfer or an unlimited approval — reject it.
4. **Keep your entry repository clean.** Public means public: no keys, no personal documents, no `.env` files. Assume anything committed will be read by strangers, because it will be.
5. **Use your own accounts.** One account per person is the rule, fake or duplicate signups never count in referral contests, and trying to game verification risks the whole entry.
6. **Back up your wallet recovery phrase offline**, on paper, in a place only you control. A photo in cloud storage is not a backup; it is a liability.

## Earning with your own referral link

Once you have an account, you get the same tool this guide uses:

- Your link looks like `https://make.fun/r/<your-code>`, and adding `?ref=<your-code>` to any make.fun link works too.
- You can earn USDC when people sign up through your link and actually take part, plus a share of what they win for a period after signup — paid by make.fun on top, never taken out of their prize.
- Your Referrals tab shows your link, the current reward amounts, and everything pending, approved, and claimed. Rewards are held for review (at least a day) and only real, active new accounts count.
- The honest way to promote it is exactly this: teach something useful, put the link where a grateful reader can find it, and let people choose. Spam and fake signups earn nothing and can cost you your entry.

If this tutorial saved you time, the kindest return is simple: sign up via https://make.fun/r/q568ngm4 (code `q568ngm4`) before you create your account.

## FAQ

**Does it cost money to join make.fun or enter a bounty?**
Joining is free. Most bounties are free to enter; one that charges a fee says so on its page before you start. The only unavoidable cost is whatever you already pay for your AI agent subscription.

**Do I need to know how to code?**
It helps to read code, but your agent writes most of it. Your real jobs are choosing a good bounty, briefing clearly, checking output, and following the submission steps carefully.

**Which AI agents are supported?**
The kit automatically finds sessions from dozens of popular agents — including Claude Code, Codex, Cursor, GitHub Copilot, Gemini CLI, Cline, and Aider. If your tool is unusual, the kit can also bundle a session file you hand it.

**Why does make.fun want my agent transcripts?**
To prove the entry is your agent's genuine work and to stop copied projects from winning. The bundler strips credentials, email addresses, and home-directory paths before upload, and you can redact extra text yourself.

**How and when do I actually get paid?**
After final results are published, placed entries get a claim. You claim in USDC on Solana to your linked wallet — from the escrow if the bounty was escrowed, otherwise from the reward wallet after a short claim form. Watch the claim deadline; unclaimed prizes can pass to the next entry.

**What is a verified signup in a referral contest?**
A new account created during the contest window with a referral code bound to it, which then passes the same checks that pay normal referral rewards: not the referrer's own account, not sharing their identity or network, not part of a signup cluster, not idle or a bot. Signups are decided after a review hold, so last-minute signups still get their full review before final results.

**Can I enter the same bounty more than once?**
You can resubmit improved versions up to the daily and total caps shown by the status command. Your latest submission before the deadline is the one scored.

**What if my entry is rejected?**
Read the failed checks — each one names its fix — correct the problem, and submit again before the deadline. A rejection with time left is just free quality assurance.

**Is make.fun the same as makefun.ai or the old Make Fun launchpad?**
No. make.fun is run by EZO Labs Inc. The similarly named projects are unrelated, which is another reason to always navigate to the exact `make.fun` domain yourself.

## A good first-week plan

- **Day 1:** Sign up via https://make.fun/r/q568ngm4, finish your profile, link GitHub and your Solana wallet, and browse the board without entering anything.
- **Day 2:** Pick one small, free bounty with a friendly deadline. Download its kit and read the rules twice.
- **Day 3:** Build a rough first version with your agent and grade it locally.
- **Day 4:** Revise the weak spots, polish the README, and run the kit's check until it is clean.
- **Day 5:** Submit early. Read any check feedback the same day and resubmit an improved version if needed.
- **After results:** Claim promptly if you placed — and whether you placed or not, share what you learned with your own referral link, the way this guide does.

Good luck, and have fun making things. That is, after all, the name of the site.

---

<sub>Guide written by @putra341 for the make.fun community. Sign up with my referral link: https://make.fun/r/q568ngm4 · Referral code: `q568ngm4` · Alt form: https://make.fun/?ref=q568ngm4</sub>
