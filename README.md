# Siege Breaker Security

Cybersecurity intelligence that publishes its own error rate.

## What We Build

Siege Breaker Security is an AI-native threat intelligence platform built around 
two core components:

**The Tracker** — an OSINT aggregation engine that collects and correlates threat 
signals from a broad range of open sources, including foreign-language sources and 
informal channels that most platforms ignore. Serves structured output via HTTP API, 
including STIX 2.1, for direct integration with SIEM and SOAR tooling.

**The Newsroom** — a multi-agent LLM pipeline that generates threat intelligence 
content: advisories, predictions, and reports. Every analytical claim is 
independently verified by multiple models before publication. If the models agree, 
it ships. If they disagree, additional models arbitrate. No single model's output 
is trusted without consensus. We call this **Tell Me No Lies**.

## How We Handle Trust

Most AI-generated content asks you to trust it. We don't.

Every forward-looking claim we publish gets a structured confidence score and a 
specific resolution criterion before it goes out. When the window closes, we score 
it publicly. Our full prediction accuracy record — including the wrong calls — lives 
in the **Prediction Ledger** on our website. You can see exactly how right and how 
wrong we've been, broken down by category, confidence tier, and time horizon.

We are transparent about our methodology because the cybersecurity community 
shouldn't have to take our word for anything.

## For Security Researchers

We have a permanent free tier for security researchers and the broader infosec 
community. No trials, no credit cards, no eventual paywalls. What we want from 
researchers is not money — it's scrutiny. Use the platform, break the methodology, 
and tell us when the output is wrong. That feedback is how this gets better.

Researcher access: [siegebreakersecurity.com](https://siegebreakersecurity.com)

To report a vulnerability in our platform: security@siegebreakersecurity.com

## Responsible Disclosure

We take responsible disclosure seriously. If the Tracker surfaces information 
suggesting a specific organization has an active, unpatched vulnerability, that 
information is handled privately and routed through coordinated disclosure channels 
before any public publication. Our full Vulnerability Disclosure Policy is published 
at [siegebreakersecurity.com/disclosure](https://siegebreakersecurity.com/disclosure).

## Status

Currently in development. Follow this organization or 
[@SiegeBreakerSec](https://x.com/SiegeBreakerSec) for updates on the public launch 
of the Tracker API and Prediction Ledger.

---

*Siege Breaker Security LLC — California*
