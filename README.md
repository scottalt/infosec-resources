# Breaking Into Cybersecurity

An opinionated guide for people trying to get their first security job.

No vendor marketing. No "just get certified" advice. No guaranteed paths.
What's here is what I wish someone had told me when I was starting.

---

## Who This Is For

People transitioning from IT, or early-career folks trying to land their first security role.

If you have zero IT experience and want to skip straight to security, read the
Common Mistakes section first.

---

## The Honest Roadmap

Most people want a straight line from "I'm interested in security" to "I have a job."
There isn't one. But there is a pattern that works:

**Build an IT foundation first.**

Security is applied IT. If you don't understand how systems work, you can't protect them.
The most consistently successful career changers I've seen followed this path:

1. Get comfortable with Windows and Linux at a basic admin level
2. Understand networking (IP, DNS, DHCP, firewalls, basic routing)
3. Learn how Active Directory / identity works. It is everywhere in enterprise.
4. Pick a direction in security (SOC, GRC, cloud, pen testing, engineering)
5. Build targeted skills and certs for that direction
6. Get hands-on time in labs or entry-level IT roles

You don't need to master all of IT. You need enough to be dangerous.

---

## Certifications

### What to get (and why)

**CompTIA Security+**
The baseline. Required for many government and enterprise roles.
Not deep, but broad. Do it early.

**SC-200 (Microsoft Security Operations Analyst)**
Underrated. If you're targeting SOC or Microsoft-heavy environments (most enterprises),
this is more practical than it looks. Covers Defender, Sentinel, and real workflows.

**Google Cybersecurity Certificate (Coursera)**
Good entry point if you're brand new. Affordable and teaches practical fundamentals
before you invest in harder certs.

**CISSP**
Not for beginners. Requires 5 years of experience to fully certify.
Worth knowing about and working toward. Associate of ISC2 is available before you qualify.

### What to skip (or deprioritize)

- CEH: Expensive, doesn't reflect real-world pen testing skills
- Any cert from a vendor you've never used: Learn the tool first
- Stacking certs without experience: Certs signal potential, not competence

### The rule

Get one cert. Get a job. Then get the next cert. Don't spend two years in cert hell
before you've touched a production environment.

---

## Hands-On Labs

This is where most people underinvest. Certs alone won't get you hired.

**Free / Low Cost**
- [TryHackMe](https://tryhackme.com): Best structured starting point for beginners
- [Hack The Box](https://hackthebox.com): More challenging, good for intermediate+
- [Blue Team Labs Online](https://blueteamlabs.online): SOC and defensive focus. Haven't used this personally, but it comes up frequently in the community.
- [LetsDefend](https://letsdefend.io): Incident response and SOC simulations
- [Immersive Labs](https://immersivelabs.com): Free for students at some universities

**Set Up Your Own Home Lab**
Running your own lab teaches you more than any platform:
- Proxmox or VirtualBox for free virtualization
- Windows Server evaluation (free 180-day trial)
- A vulnerable VM like Metasploitable or DVWA
- Network a few VMs together and practice attacks + detection

If you're targeting cloud security: spin up a free AWS, Azure, or GCP account and break things.

---

## Study Resources

**Books**
- *The Web Application Hacker's Handbook*: Web security fundamentals
- *The Practice of Network Security Monitoring* by Richard Bejtlich: SOC and NSM
- *Security Engineering* by Ross Anderson: for the deeper thinkers

**Free / Online**
- [SANS Reading Room](https://www.sans.org/white-papers/): Real research, not vendor fluff
- [MITRE ATT&CK](https://attack.mitre.org): Learn the framework. Everyone uses it.
- [Paul Jerimy's Security Certification Roadmap](https://pauljerimy.com/security-certification-roadmap/): Good visual map

**Podcasts**
- Darknet Diaries: Storytelling about real incidents, accessible to anyone
- Risky Business: Industry news for practitioners
- Security Now: Deep dives on protocol and technical topics

---

## Common Mistakes

**Skipping the IT foundation.**
Security engineers who don't understand systems struggle. You don't need years of sysadmin
experience, but you need real familiarity with how networks and operating systems work.

**Cert stacking without experience.**
Five certs and no hands-on time. Employers see this and wonder what you actually did.

**Only studying, never building.**
Set up a lab. Break something. Fix it. Document it. This is what separates candidates.

**Targeting senior roles too early.**
SOC analyst, IT help desk, junior sysadmin. These aren't beneath you.
They're how you build the foundation that makes senior roles sustainable.

**Ignoring soft skills.**
You will write reports. You will present findings to non-technical stakeholders.
You will communicate risk. If you can't write clearly, work on it.

**Not building a professional presence.**
LinkedIn matters. GitHub matters. A blog post that shows you understand something matters.
You don't need to go viral. You need to show you're engaged.

---

## Community

Find people ahead of you and stay in proximity to them.

- **ISSA (Information Systems Security Association)**: Local chapters in most cities.
  Free or low-cost student membership. Shows up on your resume.
- **OWASP**: Application security focus. Good for web/app security interests.
- **BSides conferences**: Community-run, low cost, more accessible than DEF CON or Black Hat
- **Reddit**: r/cybersecurity, r/netsec, r/AskNetsec. Search before posting.
- **Discord**: Many cert communities have study servers (TryHackMe, CompTIA, etc.)

Volunteer to help run events. Speak if you get the chance. Mentorship goes both ways.

---

## How to Use This Guide

- Pick a direction. Not "cybersecurity generally." Pick SOC, cloud, GRC, pen testing, or engineering.
- Build the foundation. At least some IT experience or equivalent self-study.
- Get one cert and one lab environment running.
- Apply before you feel ready. You'll learn more in three months on the job than in six months studying.

---

## About

Built by [Scott Altiparmak](https://scottaltiparmak.com), Senior Information Security Engineer
based in Miami. 8+ years across financial services, legal, and education.

Director of Programming, South Florida ISSA. Former President, NSU eHACKERS.

This guide ties to my work mentoring early-career engineers. If you have questions,
find me on [LinkedIn](https://linkedin.com/in/scottaltiparmak).
