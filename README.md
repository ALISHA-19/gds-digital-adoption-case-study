# Teaching a tool to someone who has never opened it

In-app guidance for **Google Data Studio**, built with the **Whatfix Community edition**: a 12-step walkthrough, a one-page flow roadmap, and a Beacon + Self Help design with use cases.

> Google Data Studio is free and powerful. It is also a blank canvas — and a blank canvas is where new users quit.

### ▶ Start here — [read the 13-page case study (PDF)](case-study.pdf)

Every step, the reasoning behind each choice, and the exact on-screen copy the user reads. It opens straight in your browser.

---

## What is in this repo

| File | What it is |
|---|---|
| [`01-walkthrough-create-your-first-data-source-report.pdf`](01-walkthrough-create-your-first-data-source-report.pdf) | The 12-step Whatfix walkthrough, exported from the live flow |
| [`02-top-5-flows-for-new-users.pdf`](02-top-5-flows-for-new-users.pdf) | One-pager: the next five journeys a beginner needs, and why |
| [`03-beacon-and-self-help-use-cases.pdf`](03-beacon-and-self-help-use-cases.pdf) | Beacon and Self Help, one slide each, with use cases and set-up |
| [`case-study.pdf`](case-study.pdf) | All three, condensed into a 12-page case study |

---

## The approach

I did not document the product. I picked the single journey that makes Data Studio click — getting your own data onto a page and watching it become a chart — and built guidance for that one journey.

**The rule I worked to:** guide the task that is high-volume or expensive to get wrong. Let the obvious stuff go.

### 1. The walkthrough — 12 steps

`Create` → `Create a report` → `Google Sheets` → pick spreadsheet → pick worksheet → review data options → `Add` → `Add to report` → drag a field → add a chart → rename → share.

Decisions worth explaining:

- **Google Sheets as the connector.** A first-time user already has a Google account and a sheet. Databases and ad accounts add credentials, and credentials are where beginners abandon.
- **"Review data options" gets its own step.** If *use first row as headers* is unticked, every field is named wrongly and the user concludes the tool is broken. Spend a step where a mistake is most expensive.
- **The two confirmations are split.** Two confirms in a row is where people hesitate — they think they already clicked it.
- **It ends on sharing, not on "now explore".** A report nobody sees has no value, and sharing is what pulls the user back tomorrow.
- **The last screen points at Self Help.** The walkthrough ends; the user's questions don't.

### 2. Top 5 flows — a funnel, not a menu

1. Create your first report — the aha moment
2. Connect and manage a data source — where "my numbers look wrong" begins
3. Start from a template — beginners freeze at a blank canvas
4. Add charts and controls — filters turn a static page into a dashboard
5. Share and schedule — adoption isn't the first login, it's the fifth

### 3. Beacon and Self Help

- **Beacon on "Chat with my data"** — new, valuable, and the one thing the walkthrough deliberately walks past. A beacon invites attention without blocking anyone, and it can be capped so it never becomes nagging.
- **Self Help on the home page** — a searchable panel holding the walkthrough plus articles and videos, scoped per page so each screen shows a short, relevant list.

---

## What I would measure next

- Completion rate of the walkthrough, and the exact step people quit at
- Time to first report created, per new user
- Support questions about building a report, before and after
- Help searches that return nothing — that list is the next thing to write

Content without a number attached is just documentation with animation.

---

## What I took away

Building the guidance was the fast part. Deciding what to leave out took longer than recording the steps.

Software is not hard to buy. It is hard to get used.

---

*Built with the Whatfix Community edition for learning purposes. Not affiliated with, or endorsed by, Whatfix or Google. All screenshots are from my own free Data Studio account.*
