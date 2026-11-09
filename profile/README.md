# linux-phone-oco

**The goal: Linux phones that are as good as Android for everyday use, and better where it
counts** - yours to control, kept up to date for as long as the hardware lasts, and free of any
one vendor.

We get there one device and one piece of hardware at a time, and everything we fix goes
**upstream** - to the mainline Linux kernel and to postmarketOS (now Nura) - so it helps every
phone and everyone who uses one, not only ours.

## How we work

- **Upstream first.** A fix that only lives here is not finished.
- **Measured, not assumed.** Every status in our docs says how we know it.
- **Real hardware in the loop.** Builds, flashing and tests run as jobs on a lab machine
  ([lab-agent](https://github.com/creation-guidelines/lab-agent)), so every step is repeatable.
- **Written down.** Findings, decisions and the plan live in [docs](https://github.com/linux-phone-oco/docs),
  not in anyone's head.

## Now

The first device is the **Xiaomi POCO X3 NFC** (`surya`, SM7150). The current front is **audio**
(the speaker, headphones and microphone); next is **power** (staying off, Android-style off-mode
charging); after that, everything else a daily-driver phone needs. The live plan is the
[backlog](https://linux-phone-oco.github.io/docs/backlog.html).

## Repositories

| | |
|---|---|
| [docs](https://github.com/linux-phone-oco/docs) | the project's memory: which phone does what, how we know, decisions, backlog, log |
| [linux](https://github.com/linux-phone-oco/linux) | our mainline kernel work for SM7150 phones, patches on their way upstream |
| [surya-lab](https://github.com/linux-phone-oco/surya-lab) | the bring-up lab for the POCO X3 NFC: device-tree audits, safe flashing, experiments |
