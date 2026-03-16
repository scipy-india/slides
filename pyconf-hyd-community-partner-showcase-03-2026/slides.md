---
theme: default
title: "SciPy India: Building Scientific Community in India"
info: |
  Presented at the PyConf Hyd open space community partner showcase, where
  multiple communities were repping themselves. Covers SciPy India's revival,
  4 community calls, the BangPypers offline collaboration, and the road to
  an annual in-person conference.
colorSchema: light
class: text-center
drawings:
  persist: false
transition: slide-left
mdc: true
fonts:
  sans: Inter
  mono: Fira Code
---

# SciPy India: Building Scientific Community in India

PyConf Hyderabad 2026 · Community Partners

<img src="/scipy_india_logo.png" class="mx-auto mt-6 h-24" />

<div class="mt-6 text-gray-600">Srihari Thyagarajan & Agriya Khetarpal</div>

<!--
Goal: set context — who we are, why we're here
Talk track: SciPy India is a community initiative revived in 2025. We're here as community partners to share what's been happening and what's coming next.
Timing: 45s
-->

---
layout: default
---

# What is SciPy India?

<v-clicks>

- Community-driven initiative, part of the broader SciPy ecosystem
- Active since **2009**, revived in **2025**
- Rooted in the Indian context of FOSS and open science
- Brings together researchers, scientists, programmers, and learners

</v-clicks>

<!--
Goal: orient the audience — what SciPy India is and why it matters
Talk track: brief, let the next slides carry the story. The revival is the key hook.
Timing: 45s
-->

---
layout: default
---

# Our Mission & Activities

<v-clicks>

- Workshops, conferences, and sprints
- FOSS + open science advocacy
- Monthly community calls — running since July 2025 (4 done so far)
- In-person events — the new direction
- **Annual SciPy India Conference** — goal: later in 2026

</v-clicks>

<!--
Goal: show the range of what we do
Talk track: pivot point — "we started online, we're going offline." The conference goal is aspirational — frame it as something we're actively working toward.
Timing: 60s
-->

---
layout: section
---

# From Online to In-Person: Our Journey So Far

---
layout: default
---

# CC#1 — July 26, 2025

First community call · Online · ~3 hours

<div class="flex gap-4 mt-6 justify-center items-start">
  <img v-click src="/cc1-1.png" class="h-44 rounded-lg shadow object-cover" />
  <img v-click src="/cc1-2.png" class="h-44 rounded-lg shadow object-cover" />
  <img v-click src="/cc1-3.png" class="h-44 rounded-lg shadow object-cover" />
</div>

<!--
Goal: show the call was real, well-attended, technically rich
Talk track: first call set the tone. Walk through each screenshot as you click — marimo dataflow, causal ML spurious correlations, subgraph matching.
Timing: 60s
-->

---
layout: two-cols
---

# CC#1 — Talks

**PyCaret** · Manjunath Janardhan
AutoML pipeline for non-experts

**marimo** · Srihari Thyagarajan
Reactive, git-friendly Python notebooks

::right::

**Causal ML + pgmpy** · Mohammad Razak
Correlation ≠ causation; probabilistic graphical models

**Subgraph Matching** · Varuni H K
Finding patterns in networks; GNNs

<!--
Goal: audience knows what was covered
Talk track: quick scan — breadth of topics is the point.
Timing: 45s
-->

---
layout: default
---

# CC#2

Online community call

<div class="flex gap-4 mt-6 justify-center items-start">
  <img v-click src="/cc2-1.png" class="h-44 rounded-lg shadow object-cover" />
  <img v-click src="/cc2-2.png" class="h-44 rounded-lg shadow object-cover" />
  <img v-click src="/cc2-3.png" class="h-44 rounded-lg shadow object-cover" />
</div>

<!--
Goal: show continued momentum
Talk track: network science (Monica), drug repurposing (Anidi), coupled neurons (Indranil). Range from social networks to bioinformatics to computational neuroscience.
Timing: 45s
-->

---
layout: two-cols
---

# CC#2 — Talks

**Online Innovation Networks** · Monica Dhani
Stack Overflow network science with NetworkX

**AI Drug Repurposing** · Anidi Pendiala
LLMs + GNNs on ChEMBL and PubMed datasets

**Neuroscience ODEs** · Indranil
Chaos and synchronization in coupled neuron models

::right::

**SKtime Forecasting** · Mridul Jain
Hierarchical + probabilistic forecasts

**Mojo** · Abhijit
Python superset with C++-level performance

<!--
Goal: show breadth — bioinformatics to language design
Timing: 45s
-->

---
layout: default
---

# CC#3

Online community call · [Recording on YouTube](https://youtu.be/6SoLgkFVkIg)

<div class="flex gap-4 mt-6 justify-center items-start">
  <img v-click src="/cc3-1.png" class="h-44 rounded-lg shadow object-cover" />
  <img v-click src="/cc3-2.png" class="h-44 rounded-lg shadow object-cover" />
  <img v-click src="/cc3-3.png" class="h-44 rounded-lg shadow object-cover" />
</div>

<!--
Goal: show the call is publicly accessible
Talk track: OpenFOAM node editor (Navya), Astrolab astronomy toolkit (Philip), cosmic web galaxy clustering. Recording is public — good to mention.
Timing: 45s
-->

---
layout: two-cols
---

# CC#3 — Talks

**OpenFOAM Node Editor** · Navya Sai Sadhu
Visual programming for fluid dynamics via pynt

**Astrolab** · Philip
Python toolkit for undergrad astronomy — photometry, spectroscopy

::right::

**Cosmic Web**
Galaxy alignment + tidal torque theory with Astropy

**Nix for Python** · Vivekananda
Declarative package management; goodbye dependency hell

<!--
Goal: audience sees fluid dynamics to astronomy to packaging tooling
Timing: 45s
-->

---
layout: default
---

# CC#4 — December 6, 2025

Online community call · Closed out 2025 strong

<div class="flex gap-6 mt-6 justify-center items-start">
  <img v-click src="/cc4-1.png" class="h-44 rounded-lg shadow object-cover" />
  <img v-click src="/cc4-2.png" class="h-44 rounded-lg shadow object-cover" />
</div>

<!--
Goal: wrap up the online call arc
Talk track: Chandasu — Telugu metrical poetry analysis (language + culture + CS intersecting). Ramanujan — custom interpreter + distributed compute. Walk through each screenshot.
Timing: 45s
-->

---
layout: two-cols
---

# CC#4 — Talks

**Chandasu**
Python framework + 4,600-poem dataset for Telugu metrical poetry analysis

**Ramanujan** · Pranav
C++ interpreter (17% faster than CPython) + DAG-based distributed compute

::right::

**PhiFlow** · Sadna & Abel
Differentiable fluid simulations in Python (PyTorch / JAX / TF backends)

<!--
Goal: Chandasu is the standout — linger on it briefly
Talk track: language + culture + CS in one talk is exactly the kind of thing SciPy India wants to amplify.
Timing: 45s
-->

---
layout: section
---

# Taking It Offline

---
layout: two-cols
---

# SciPy India × BangPypers — Feb 21, 2026

**Venue:** Amadeus Software Labs, Bengaluru

~3.5h afternoon event · Joint CFP across both communities

::right::

**Garbage In, Garbage Out** · Anirudh Sethuraman
Reliable LLM systems, data pipelines, LlamaIndex tradeoffs

**From User to Maintainer** · Ganesh Kathiresan *(NumPy maintainer)*
`show_runtime()`, `bitwise_count()`, 80% int-division speedup

**Python Annotations & t-strings** · Tushar Sadhwani
PEP 750, live demos — ran long in the good way

**Lightnings:** Load balancing (Nischal) · Metagenomics/Kraken2 (Anand)

<!--
Goal: make the offline moment feel tangible
Talk track: mention FOSSHack community partner pitch at the close — good forward-looking note.
Timing: 90s
-->

---
layout: quote
---

# "A couple of people walked up afterwards saying they wanted to get involved with SciPy India. That counts for more than a dozen online signups."

— SciPy India × BangPypers meetup blog

<!--
Goal: land the case for in-person
Talk track: let it breathe. Don't explain it.
[FLAG FOR HUMAN REVIEW] Verify this quote is verbatim from the blog post before the talk.
Timing: 20s
-->

---
layout: default
---

# What's Next

<v-clicks>

- More in-person collaborations with local Python communities
- [FOSSHack 2026](https://fossunited.org/hack/fosshack26) — SciPy India & BangPypers as community partners
- **Annual SciPy India Conference** — planning in progress ([GitHub issue #17](https://github.com/scipy-india/planning/issues/17))
- Goal: restart the in-person conference series (last held 2021)

</v-clicks>

<!--
Goal: forward momentum — there's more coming
[FLAG FOR HUMAN REVIEW] Verify all links are live before the talk.
Timing: 60s
-->

---
layout: two-cols
---

# Get Involved

**How to participate:**

- Join the community on Zulip chat
- Attend events — calls, workshops, meetups
- Contribute to open source: code, docs, testing
- Share knowledge: blog posts, talks, workshops
- Volunteer: outreach, planning, comms

::right::

**Links:**

- Website: [scipy-india.github.io](https://scipy-india.github.io)
- GitHub: [github.com/scipy-india](https://github.com/scipy-india)
- Zulip: [scipyindia.zulipchat.com](https://scipyindia.zulipchat.com)
- FOSS United: [fossunited.org/c/scipy-india](https://fossunited.org/c/scipy-india)
- LinkedIn · Mastodon · Bluesky

<!--
[FLAG FOR HUMAN REVIEW] Verify all links resolve before the talk.
Timing: 45s
-->

---
layout: end
---

# Join the SciPy India community!

<img src="/qr-code.png" class="mx-auto mt-4 h-40" />

<div class="mt-4 text-gray-500">scipy-india.github.io</div>

<!--
Goal: CTA — get people to scan and join
Talk track: invite questions. QR links to Zulip — verify before the talk.
[FLAG FOR HUMAN REVIEW] Confirm QR code destination is still valid.
Timing: 30s + Q&A
-->
