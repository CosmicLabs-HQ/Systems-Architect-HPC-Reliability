# Systems-Architect-HPC-Reliability

# Systems Architect, HPC & Reliability

**Location:** In-person, San Francisco (Relocation Supported)
**Type:** Full-time | Competitive Pay + Equity
**Start Date:** ASAP

## What You'll Own

You will own the systems-level view of what our models see and what they predict. Cosmic operates at the intersection of AI and physical infrastructure, and this role owns the reliability layer: the failure taxonomies, the telemetry and log signals that matter, and the fault tolerance architecture the models reason over. You decide what a failing GPU or a degrading link actually looks like in the data, and you keep that picture coherent from the silicon up.

This is a hard systems problem, and it lives low in the stack. Fleet telemetry is fragmented across vendors, hardware generations, and firmware versions. Failure signatures are subtle, often vendor-specific, and rarely documented. Ground truth on what actually failed is sparse and inconsistent, and the systems are non-stationary as hardware ages, firmware changes, and workloads shift underneath you. The cost of getting it wrong is not a noisy dashboard but a missed failure on a system where downtime has real consequences.

You will:

- Define the failure modes and reliability signals that matter across GPU and CPU fleets, including XID errors, silent data corruption, HBM thermal events, NVLink degradation, ECC and memory trends, and firmware and BMC behavior
- Correlate device telemetry, firmware and BMC state, and link-level network signals into a single coherent picture of fleet health
- Map those failure modes to the telemetry and log sources that expose them, and shape the data architecture for what Cosmic ingests and how it feeds the System Behavior Models
- Analyze production telemetry from supercomputers and AI clusters to find the patterns that precede hardware failure, and turn those patterns into prediction targets the models can learn from
- Design fault tolerance and resilience approaches at the hardware and fabric layer, covering failure domains, degraded-mode operation, and recovery
- Work directly with design partners across national labs, neoclouds, and hyperscalers to validate failure taxonomies against real incident history
- Partner with the research and infrastructure teams to translate fleet behavior into model features and evaluation criteria

## What You Bring

- 4+ years working close to the hardware in large-scale HPC, AI, or cloud fleets, at the level of silicon, firmware, and the network fabric
- Hands-on experience with device and fabric telemetry, such as GNMI, Redfish and BMC data, NVIDIA DCGM, and link-level network signals, used to diagnose or predict hardware faults
- Experience building a prediction, anomaly detection, or reliability analysis system against real operational data, and a clear sense of where those systems break
- Strong grounding in fault tolerance and resilience at the hardware and fabric layer, including failure domains and RAS
- The ability to sit between the hardware layer and the data and modeling layer without losing precision in either one
- Strong software engineering habits: clean code, version control, reproducible work, testable pipelines
- Ability to work independently on open-ended problems and communicate clearly with engineers who do not share your background

## Bonus

- Direct experience with NVIDIA GPU fleets and the failure surface around them, including XID and SDC analysis, HBM failure characterization, or NVLink behavior
- Low-level networking depth, including link-level fabric health, GNMI, and large-scale interconnect such as InfiniBand, NVLink, or Slingshot
- A telecom or networking background where you worked below the application layer
- Background in firmware, BMC, or hardware bring-up
- Time inside a national lab, hyperscaler, or neocloud reliability or SRE organization
- US person status and the ability to obtain a security clearance, which is a plus generally and a requirement for certain projects

## Why Cosmic Labs

Cosmic is a hardware intelligence platform used across critical compute infrastructure. We have access to a proprietary data layer that most organizations generate but nobody has built real prediction on top of. The data exists, the problem is unsolved, and the operators who depend on this infrastructure need predictions they can act on, not dashboards they have to interpret. The product is deployed today with national lab and defense buyers, with active pilots across neoclouds, hyperscalers, and system integrators.

If you have spent your career close to the hardware and want to work on the systems and reliability problems behind a deployed product, with direct access to fleet data most engineers never get to touch, we want to hear from you.

## How to Apply

Email the following to **team@cosmiclabs.io**:

**Subject line:** Member of Technical Staff, Systems Architecture / [Your Name]

In the body:

- Your name
- Why this role and why Cosmic Labs
- What you bring technically
- Soonest available start date
- Education and years of experience
- U.S. work eligibility status
- Availability (dates and times) for a 15-minute phone call over the next seven days

**Attachment:** PDF resume

Applications reviewed on a rolling basis.
