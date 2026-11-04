# PhishFood

> "Oh heavens, I've been phished!"

Small Singapore offices are on the menu.

Fake IRAS tax refunds. Fake Singpass suspensions. Fake SingPost delivery fees. Attackers are serving these up daily, and most small offices have no IT team, no incident plan, and a vague sense that PDPA is something they should probably look into at some point.

PhishFood is for them.

---

## What's in here

**[`analysis.md`](01-phishing-simulation/analysis.md) — The Simulation**

A controlled phishing simulation run in an isolated lab environment against dummy accounts I own. Three campaigns: fake IRAS tax refund, fake Singpass suspension, fake SingPost delivery notice. Documents the full attack chain from spoofed email to harvested credentials — so you know exactly what you're defending against.

**[`checklist.md`](02-pdpa-checklist/checklist.md) — The PDPA Checklist**

Plain-English. No legal jargon (I'm not a lawyer), no IT degree required. Five things every small Singapore office should check before something goes wrong.

**[`incident-card.md`](03-incident-response-card/incident-response-card.md) — The Incident Response Card**

What to do in the first 60 minutes if something goes wrong. Three scenarios: clicked a suspicious link, gave away a password, money left the account. Print it. Stick it on the wall. Hope you never need it.

**[`why-it-works.md`](why-it-works.md) — Why It Works**

Why these emails fool people, what psychological buttons they press, and the one habit that stops all of them.

---

## Who this is for

A 10-person Singapore organisation with no dedicated IT team that handles personal data — NGOs, law firms, arts organisations, libraries.

---

## What this is not

This is not legal advice. The simulation was conducted entirely in an isolated lab environment against dummy accounts. No real users were targeted. No actual phishing emails were sent to anyone who didn't ask for them.

*(TLDR: Please don't sue me.)*

For actual PDPA compliance questions, consult the [PDPC](https://www.pdpc.gov.sg) or a qualified data protection officer. For real cyber incidents, contact [CSA SingCERT](https://www.csa.gov.sg/singcert).

---

## Built with

| Tool | Purpose |
|------|---------|
| GoPhish v0.12.1 | Phishing simulation framework |
| Kali Linux | Isolated attacker environment |
| Mailtrap | Safe SMTP sandbox |
| VMware Workstation Pro | Virtualisation |

---

## What this demonstrates

- Real phishing attack simulation in an isolated lab environment
- Understanding of Singapore's regulatory context (PDPA)
- Translating technical concepts for non-technical humans
- Shipping something complete and actually usable