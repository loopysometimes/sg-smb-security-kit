# PhishFood!

> "Oh heavens, I've been phished!"

**Small Singapore offices are on the menu?!**


Fake IRAS tax refunds. Fake Singpass deletions. Fake SingPost delivery fees. Attackers are serving these up daily, and some small offices have no IT team, no incident plan along with a vague sense that PDPA is  something they should probably look into at some point.

PhishFood is for them.

---


## What's in here


**[`analysis.md`](analysis.md) — The Simulation**
A controlled phishing simulation run in an isolated lab environment against dummy accounts I own. Three campaigns: fake IRAS tax refund, fake Singpass deletion, fake SingPost delivery notice. Documents the full attack chain from spoofed email to harvested credentials — so you know exactly what you're defending against.

**[`checklist.md`](checklist.md) — The PDPA Checklist**
A plain-English checklist for small Singapore organisations. No 
legal jargon (I legally can't add that since I'm not a laywer), no IT degree required. Five things to check before something goes wrong.

**[`incident-card.md`](incident-card.md) — The Incident Response Card**What to do in the first 60 minutes if something goes wrong. Three scenarios: clicked a suspicious link, gave away a password, money left the account. Print it. Stick it on the wall. Hope you never need it.

**[`why-it-works.md`](why-it-works.md) — Why** A short rundown on why these phishing emails work, how they work, and how to avoid them!
---

## Who this is for

A 10-person Singapore organisation with no dedicated IT team who handle 
personal data.
---

## What this is not

This is not legal advice. The simulation was conducted entirely in an 
isolated lab environment against dummy accounts. No real users were 
targeted. No actual phishing emails were sent 

(TLDR: Please don't sue me)

For actual PDPA compliance questions, consult the [PDPC](https://www.pdpc.gov.sg) or a qualified data protection officer.


For real cyber incidents, contact [CSA SingCERT](https://www.csa.gov.sg/singcert).
---

## Built with

- GoPhish v0.12.1
- Kali Linux
- Mailtrap
- VMware Workstation pro

This project should/does demonstrate
- Real phishing attack simulation using GoPhish in an isolated lab environment
- Understanding of Singapore's regulatory context (PDPA)
- Ability to translate technical concepts for non-technical audiences
- Practical security awareness resources that organisations can use immediately