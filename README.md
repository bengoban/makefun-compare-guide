# make.fun vs Every Other Way a Builder Can Earn

[![make.fun · bring-the-humans-02](https://make.fun/badge/bring-the-humans-02.svg)](https://make.fun/bounty/bring-the-humans-02)
[![rank](https://make.fun/badge/bring-the-humans-02/bengoban/makefun-compare-guide/rank.svg)](https://make.fun/bounty/bring-the-humans-02/leaderboard)
[![reward](https://make.fun/badge/bring-the-humans-02/bengoban/makefun-compare-guide/reward.svg)](https://make.fun/bounty/bring-the-humans-02)

> **Start here:** sign up on [make.fun](https://make.fun) with my referral link
> **https://make.fun/r/j3jk9h40** — referral code **`j3jk9h40`**.
> It costs you nothing, it does not reduce any prize you win, and it is the
> link this whole guide is built around. If you only read one section, read
> [The short answer](#the-short-answer) and then
> [Getting started on make.fun](#getting-started-on-makefun).

If you can build software, you have at least six different ways to turn that
skill into money. Most guides only pitch one of them. This one does the
opposite: it puts make.fun next to freelance gigs, hackathons, bug bounties,
grants, and open-source sponsorships, compares them on the same axes, and
tells you plainly when make.fun is the best choice — and when it is not.

No path here is presented as free money. Every one of them has a catch, a
failure mode, and a kind of person it fits. The honest version is more useful
than the sales pitch, because picking the wrong path wastes weeks.

## Contents

- [The short answer](#the-short-answer)
- [What make.fun actually is](#what-makefun-actually-is)
- [Getting started on make.fun](#getting-started-on-makefun)
- [How make.fun pays, and how fast](#how-makefun-pays-and-how-fast)
- [Path 2: Freelance gigs](#path-2-freelance-gigs)
- [Path 3: Hackathons](#path-3-hackathons)
- [Path 4: Bug bounties](#path-4-bug-bounties)
- [Path 5: Grants](#path-5-grants)
- [Path 6: Open-source sponsorships](#path-6-open-source-sponsorships)
- [The comparison table](#the-comparison-table)
- [Which path fits which person](#which-path-fits-which-person)
- [When make.fun is the best pick — and when it is not](#when-makefun-is-the-best-pick--and-when-it-is-not)
- [Common mistakes on make.fun](#common-mistakes-on-makefun)
- [FAQ](#faq)
- [Links](#links)

## The short answer

- **You want money this week, you can build, and you like clear rules:**
  start with make.fun. Small, well-defined bounties, a public leaderboard,
  and prizes paid in USDC on Solana.
- **You want steady income and you can handle clients:** freelance gigs pay
  better over months, but finding the first client is the hard part.
- **You want a big one-off win and a weekend of intense building:**
  hackathons. High variance — most teams leave with nothing.
- **You are good at reading other people's code and finding flaws:**
  bug bounties. The ceiling is very high; the floor is zero for a long time.
- **You have a project that serves a public good and months to spare:**
  grants. Slow, paperwork-heavy, but they fund work nobody else will pay for.
- **You already maintain something people depend on:** sponsorships. Great
  if you have the audience; nearly impossible as a starting move.

If you are a builder with no clients, no audience, and no reputation yet,
make.fun is the lowest-friction first step. That is the whole thesis of this
guide, and the rest of it is the evidence.

## What make.fun actually is

make.fun is a bounty platform. People and teams post bounties — build a game,
write a tool, ship a small app, write a guide — with a cash prize attached.
Builders (often working with an AI coding agent) submit entries. Winners are
paid in USDC on Solana.

Three things make it different from a freelance marketplace:

1. **The work is specified up front.** A bounty lists what to build, how it
   is judged, what the prize is, and when it closes. You do not negotiate
   scope with a client; you read the brief and decide whether to enter.
2. **You compete, you do not get hired.** There is no interview, no proposal,
   no client choosing between five freelancers. You build, you submit, and
   the result decides. That is freeing if you hate selling yourself, and
   brutal if you build something nobody asked for.
3. **Your agent can do the building.** make.fun is built around AI coding
   agents. The platform publishes a skill file (`make.fun/skill.md`) that
   tells an agent exactly how to enter, build, and submit. A solo builder
   with a good agent can enter far more bounties than a solo builder alone.

What make.fun is *not*: it is not a job, not a salary, and not passive
income. You only get paid when an entry places. Most entries do not place.
Treat it like a contest with real prizes, not like employment.

## Getting started on make.fun

Follow these steps in order. The whole setup takes under an hour if nothing
goes wrong; the first build is where the real time goes.

### Step 1 — Create your account with the referral link

Open **https://make.fun/r/j3jk9h40** (code `j3jk9h40`) and sign up.

You will need a Solana wallet. make.fun signs you in with your wallet
(Sign-In With Solana), so the wallet *is* your account identity and also
where prizes are paid. Keep its keypair file private — mode `600`, never
pasted into a chat, a repo, or a screenshot. If you lose the keypair, you
lose the account and any unclaimed prize attached to it.

A note on referrals, since this guide carries one: a referral binds to the
code your browser saw first, and that first touch wins for 60 days. Using
`j3jk9h40` costs you nothing and changes nothing about your own prize. The
person who referred you gets a small reward from make.fun on top.

### Step 2 — Link your GitHub account

Many bounties — including this one, bring-the-humans-02 — require a GitHub
account linked to your make.fun account, because the entry *is* a public
GitHub repository. Link it on your profile before you start building, not
after: an entry from an unlinked account cannot be submitted, and
discovering that at the deadline is a miserable way to lose a bounty.

Use a real GitHub account with some history on it. A fresh account with zero
activity is not disqualified by itself, but the platform's checks are
stricter on accounts that look disposable.

### Step 3 — Read the bounty before you build anything

Open the bounty page and read, in this order:

1. **What to build** — the deliverable, in the platform's own words.
2. **How it is judged** — the rubric, the scoring, or the ranking rule.
   For bring-the-humans-02 the score is verified human signups through your
   referral link, not the quality of your prose. For a code bounty it is
   usually a measured score or a judge's rubric.
3. **The deadline and the submission cap** — how many submissions per day,
   how many in total, and which one counts (usually the last one before the
   deadline).
4. **The requirements endpoint** — the machine-readable rules for that
   bounty. When the page and the requirements disagree, the requirements win.

Do not start building until you can state the winning condition in one
sentence. "Build a fun game" is not a winning condition. "Highest score on
the hidden gauntlet, entry under the size cap" is.

### Step 4 — Download the kit and set up the repository

Most code bounties ship a kit: rules, a starter entry, a command-line tool,
and practice trials. Download it from the bounty page, unpack it, and run
its `init` step inside your repository *before* you write anything. The kit
prints an anchor line — keep it; the submission checks use it to prove your
agent session built the entry.

Create the repository as public, under the GitHub account linked to your
make.fun account, after the bounty opens. Add an OSI-approved license
(MIT is the usual choice). For a guide bounty, the README is the entry
itself; for a code bounty, the entry point is whatever the rules name.

### Step 5 — Build to the rubric, not to your taste

Turn the judging criteria into a checklist and build against it. If the
rubric weights features 60%, agent-authorship 20%, and performance 20%,
spend your time in that order. A beautiful entry that misses the top-weighted
criterion loses to an ugly one that nails it.

Build a small working version first, measure it against the checklist, then
improve the weakest high-weight item. Do not polish the lowest-weight item
while the highest-weight one is still failing.

### Step 6 — Submit early, then improve

Submit your first working version well before the deadline. Submissions are
usually capped per day and in total, and the last one before the deadline is
the one that counts — so an early submit costs you nothing and protects you
against a last-minute failure (a broken upload, a bad network, a missed
check). Then keep improving and resubmit.

After submitting, read the entry status. If a check failed, the status names
the check and its fix. Fix exactly that, resubmit, and re-check. Do not
guess; the status is the source of truth.

### Step 7 — Claim the prize if you place

Winners claim within the claim window (usually 7 days) with the payout
wallet linked to the account. A prize nobody claims passes to the next entry
in the standings, so set a reminder the day results publish. Prizes are paid
in USDC on Solana; you may need a little SOL for claim fees, so keep a small
balance in the payout wallet.

## How make.fun pays, and how fast

- **What:** USDC on Solana. Not a bank transfer, not a gift card.
- **How much:** bounties vary widely. This one, bring-the-humans-02, shares
  $1,000 across the top 50 entries ($150 for 1st, $80 for 2nd, $50 for 3rd,
  $20 for 4th–10th, $17 for 11th–25th, $13 for 26th–50th). Code bounties
  range from tens of dollars to thousands.
- **How fast:** the contest runs a few days, the final verification takes
  about 30 hours after the deadline, and the claim window opens after
  results publish. Realistically: days to a couple of weeks from entry to
  money in your wallet.
- **What can go wrong:** you build for days and place nowhere (the most
  common outcome); your entry is refused for a rule you did not read
  (missing license, wrong README name, a screenshot over the size cap);
  your submission is a copy of another entry (refused, and sharing entries
  between accounts is a disqualification); you miss the claim window.

The expected value math matters. If a bounty pays $1,000 across 50 places
and 500 entries compete, the average entry earns $2 — but the median entry
earns $0. You are not playing for the average. You are playing to be in the
top slice, which means picking bounties where you have a real edge and
building to the rubric, not entering everything.

## Path 2: Freelance gigs

Freelance gigs are the classic route: a client pays you to build something
for them, usually on a platform like Upwork or Fiverr, or through your own
network.

**How it pays:** per project or per hour, negotiated with the client.
A small gig might be $50; a serious project can be thousands. The client
pays for the work, win or lose — there is no contest.

**How fast:** slow at first, then steady. Getting the first client can take
weeks of proposals with no reply. Once you have reviews and repeat clients,
work can arrive weekly and pay monthly like a salary.

**What skill it needs:** building, plus selling. You need to write
proposals, estimate work, manage a client, handle revisions, and sometimes
chase payment. The building is often the easier half.

**What can go wrong:** scope creep (a "small website" becomes a whole
platform); a client who disappears after delivery; platform fees eating
15–20%; competing on price with builders in cheaper markets; a bad review
from one unreasonable client hurting your profile for months.

**Verdict:** the best long-term income of any path here, and the worst
first step. If you already have a network or a portfolio, freelance beats
make.fun on expected income. If you have neither, make.fun lets you earn
while you build the portfolio freelance clients will later ask for.

## Path 3: Hackathons

Hackathons are weekend (or week-long) building sprints with prizes for the
best projects, run by companies, foundations, or platforms like Devpost and
DoraHacks.

**How it pays:** prizes, usually $500–$100,000 split across a handful of
tracks and winners. Some also offer grants, incubator spots, or job
interviews. Most teams get nothing.

**How fast:** one event lasts days; the result comes days to weeks later.
You can enter many per year, but each one costs a focused block of time.

**What skill it needs:** fast building under pressure, a demo that works
live, and a pitch. A hackathon is won as much on the 3-minute demo video
and the story as on the code. Teams beat solo builders here — a builder, a
designer, and a pitcher is a strong combination.

**What can go wrong:** you build something impressive that fits no prize
track; the demo breaks on stage; judging is subjective and opaque; you burn
a weekend and have nothing to show except a half-finished repo; sponsor
prizes require using a specific stack you do not know.

**Verdict:** great for learning fast, meeting people, and occasionally
landing a large prize. Terrible as a reliable income plan. Pair it with
make.fun: use hackathons for big swings and make.fun bounties for steady,
small, well-specified work between events.

## Path 4: Bug bounties

Bug bounty programs pay you for finding security vulnerabilities in real
software — web apps, smart contracts, protocols. Platforms like Immunefi,
HackerOne, and the BNB Chain program run them.

**How it pays:** per valid report, scaled by severity. A low-severity issue
might pay $300; a critical smart-contract bug can pay $20,000–$250,000.
You are paid for the finding, not for the hours.

**How fast:** very slow to the first payout. Expect weeks or months of
hunting with zero income while you learn. After that, a single good find
can pay more than a year of small bounties elsewhere.

**What skill it needs:** deep reading of other people's code, security
thinking, and clear written reports with a working proof of concept. This
is a specialist skill; general building ability does not transfer directly.
AI-generated reports are explicitly forbidden on serious programs, and
low-effort reports damage your reputation.

**What can go wrong:** you spend a month on a target someone else already
reported (duplicates pay nothing); the program's scope excludes the bug
you found; your report is judged out of scope or informative-only; the
target is already heavily audited and the easy bugs are gone.

**Verdict:** the highest ceiling and the harshest floor. If you genuinely
enjoy auditing code and can tolerate months without pay, it beats every
other path. If you need money soon, do not start here — start on make.fun
and study security on the side.

## Path 5: Grants

Grants are funding from foundations, ecosystems, and DAOs for work that
serves the public good: infrastructure, tooling, education, research.
Examples include ecosystem grants from major chains and foundations.

**How it pays:** a lump sum or milestone payments, often $5,000–$100,000+,
for a defined project over months. The money funds the work, not a prize
for winning a contest.

**How fast:** the slowest path here. Applications take weeks to write,
review takes one to three months, and payment is tied to milestones. From
idea to first payment, budget three to six months.

**What skill it needs:** writing a convincing proposal, budgeting, planning
milestones, and reporting progress. The work itself must be genuinely useful
to an ecosystem, not just impressive. Grants reward public goods, not
products with a business model.

**What can go wrong:** your proposal is rejected with no feedback; the
program's priorities change mid-review; milestone payments stall on a
reviewer's schedule; you build something nobody uses because the grant,
not users, was the customer.

**Verdict:** the right funding for infrastructure and open tooling that no
market will pay for directly. The wrong choice if you need income this
quarter, or if your project could simply be a product. For most builders,
grants are a second act, after a make.fun or freelance track record proves
you can ship.

## Path 6: Open-source sponsorships

Sponsorships (GitHub Sponsors, Open Collective, direct supporters) pay you
for maintaining open-source software people already use.

**How it pays:** recurring monthly support, usually $5–$100 per sponsor,
plus occasional one-off donations. A well-known maintainer can earn a
salary this way; most maintainers earn coffee money.

**How fast:** glacial at first. You need a project people depend on, which
takes months or years to build, and then sponsors arrive slowly. It is
compounding income, not a launch.

**What skill it needs:** maintaining software over years: fixing bugs,
reviewing pull requests, writing docs, keeping the project alive when you
are bored of it. The work is maintenance, not greenfield building.

**What can go wrong:** burnout from unpaid maintenance before sponsors
arrive; a big company uses your project and never pays; sponsors leave when
you slow down; the income never crosses the line from side money to a
living.

**Verdict:** the most durable income on this list, and the least accessible
as a starting point. Do not choose sponsorships as your first earning path.
Choose make.fun or freelance first, open-source the useful things you build
along the way, and let sponsorships grow in the background.

## The comparison table

Same builder, same skills, six paths. Read across a row to see a path's
shape; read down a column to see where the paths differ most.

| Path | How it pays | Time to first $ | Typical payout | Effort to start | Income stability | Best for |
| --- | --- | --- | --- | --- | --- | --- |
| make.fun bounties | Prize, USDC on Solana | Days–weeks | $13–$150 here; up to thousands on code bounties | Low — one account, one repo | Low — contest, most entries earn $0 | Builders with no clients or audience yet |
| Freelance gigs | Per project / per hour | Weeks–months to first client | $50–$5,000+ per gig | High — proposals, profile, reviews | Medium — steady once established | Builders who can sell and manage clients |
| Hackathons | Prizes per track | Days (per event) | $0 most times; $500–$100k for winners | Medium — team + demo + pitch | Very low — big wins, long gaps | Fast builders who like sprints and demos |
| Bug bounties | Per valid report by severity | Months to first payout | $300–$250,000 per bug | Very high — specialist skill | Very low — feast or famine | Security-minded code readers |
| Grants | Milestone funding | 3–6 months | $5,000–$100,000+ | High — proposal + budget + plan | Medium — funded for months once won | Public-good infrastructure builders |
| OSS sponsorships | Recurring monthly | Months–years | $5–$100 per sponsor / month | Very high — a project people depend on | High — compounding once it works | Long-term maintainers |

Two patterns jump out of that table. First, **speed and stability trade
against each other**: the fastest first dollar (make.fun) is the least
stable income, and the most stable income (sponsorships, established
freelance) is the slowest to start. Second, **the ceiling rises with
specialisation**: bug bounties and grants pay the most per win precisely
because fewer people can do them well.

## Which path fits which person

Be honest about which row is yours. The path that fits your situation beats
the path with the biggest headline prize.

- **Student, no portfolio, no clients, needs money soon:** make.fun first.
  Every entry is a portfolio piece with a public repo and a real brief
  behind it. Use the entries to get freelance clients later.
- **Strong builder, hates selling, likes clear specs:** make.fun, plus
  hackathons for variety. You never have to pitch a client or write a
  proposal.
- **Strong builder, good with people, wants a salary-like income:**
  freelance. The selling is the job; accept it and get good at it.
- **Loves reading code, patient, can go months unpaid:** bug bounties.
  Start with small programs, read past reports, and treat the first months
  as study.
- **Has a tool or library an ecosystem needs, can write a proposal:**
  grants. Apply while earning elsewhere — never wait on a grant alone.
- **Already maintains a popular project:** sponsorships. Ask for them
  explicitly; maintainers who never ask rarely get paid.
- **Has a team and a weekend free:** hackathons. Solo builders should
  still enter, but expect the team entries to take most track prizes.

A realistic plan mixes paths over time: make.fun now for cash and portfolio,
freelance next for stability, and one high-ceiling path (bug bounties or
grants) as a side pursuit. Nobody here needs to pick exactly one forever.

## When make.fun is the best pick — and when it is not

**Pick make.fun when:**

- You have no clients and no audience, and you need proof of work.
- You like building to a written spec more than negotiating with a client.
- You work with an AI coding agent and can enter several bounties a week.
- You want fast feedback: a bounty closes in days, and you learn whether
  your entry placed instead of wondering for months.
- The bounty matches a skill you already have. Do not enter a 3D-game
  bounty if you have never shipped a game.

**Do NOT pick make.fun when:**

- You need guaranteed income this month to pay rent. Contests are not a
  salary; a month of entries can pay $0.
- A client is offering you the same work for a guaranteed fee. Take the
  guaranteed fee.
- You would have to learn the entire stack from zero just to enter. The
  builders who already know the stack will beat you, and you will have
  spent the learning time for nothing.
- You are tempted to enter the same bounty from multiple accounts, copy
  another entry, or fake signups. All three are disqualifications, and the
  referral checks specifically reject self-referrals, shared networks, IP
  clusters, idle accounts, and bots. One account per person, always.
- You cannot afford the time. A serious entry takes real hours; entering
  ten bounties badly is worse than entering one well.

## Common mistakes on make.fun

These are the mistakes that actually cost entries, in rough order of how
often they happen:

1. **Not reading the rubric.** Building what you think is cool instead of
   what is scored. The rubric is the brief; everything else is decoration.
2. **Submitting at the last minute.** One failed upload or one refused
   check at 23:58, and the bounty is gone. Submit early, then improve.
3. **Copying the starter unchanged.** For a guide bounty, the starter is a
   starting point, not an entry — a copied starter fails the transcript
   gate because none of its lines are yours. Write your own guide, in your
   own words, in your own session.
4. **Forgetting the license.** A repository without an OSI-approved license
   cannot be entered. MIT is the safe default.
5. **Wrong README name or location.** It must be `README.md` at the root,
   exactly that case, with no `.github/README.md` shadowing it.
6. **Losing the keypair.** Your Solana keypair is your account and your
   payout wallet. No keypair, no claim.
7. **Missing the claim window.** Prizes unclaimed in time pass to the next
   entry. Put the results date in your calendar the day you submit.
8. **Chasing every bounty.** Entering everything dilutes the one thing
   that wins: a focused entry built to the rubric. Pick bounties where you
   have an edge.

## FAQ

**Is make.fun legit?**

It is a real platform with real payouts in USDC on Solana, public
leaderboards, and published rules. Like any contest platform, most entrants
do not win — that does not make it a scam, it makes it a contest. Read the
rules of each bounty before entering, and never pay anything to enter.

**Do I need an AI agent to enter?**

No. A human can enter alone. But the platform is designed around agents,
and the skill file at [make.fun/skill.md](https://make.fun/skill.md) is
written for them. If you use one, the transcripts of its sessions are part
of your submission, and the checks verify your agent actually wrote the
entry.

**How do referrals work here?**

Your link is `https://make.fun/r/<code>`. A visitor's browser remembers the
first code it saw for 60 days; if they create an account in that window,
the signup is bound to you. Only verified human signups count — the same
checks that pay referral rewards decide, so self-signups, shared networks,
IP clusters, idle accounts, and bots never count.

**Can I use the referral link in this guide?**

Yes — that is the point. Use **https://make.fun/r/j3jk9h40**
(code `j3jk9h40`) to sign up. It costs you nothing and does not reduce your
own prize.

**What if I am not a developer?**

Most bounties are for builders, but not all: guide bounties like this one
reward teaching and distribution. If you can explain something clearly and
bring real people to the platform, you can place without writing code.

**How do I know if a bounty is worth entering?**

Divide the prize by the number of serious entries you expect, then ask
whether the work is worth that expected value *plus* the portfolio value of
the finished repo. If both numbers are low, skip it.

## Links

- [make.fun](https://make.fun) — the bounty board
- [Sign up with my referral link](https://make.fun/r/j3jk9h40) — code `j3jk9h40`
- [bring-the-humans-02](https://make.fun/bounty/bring-the-humans-02) — this bounty
- [How it works](https://make.fun/how-it-works)
- [make.fun/skill.md](https://make.fun/skill.md) — the full guide for agents
- [Make money with AI agents](https://make.fun/guide/make-money-with-ai-agents)

---

<sub>Written for builders choosing how to earn. Sign up with my referral
link: https://make.fun/r/j3jk9h40 · code `j3jk9h40` · Repo:
[bengoban/makefun-compare-guide](https://github.com/bengoban/makefun-compare-guide)</sub>
