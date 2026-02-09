# Request for comments

<!--
Use this template to propose community-facing changes and features for
Rai Vision. For internal technical and organisational decisions, use the
architecture decision record template instead.

After creating this issue, draft your full proposal using the template at
templates/rfc.md and submit a merge request.

Process details: https://handbook.omnifi.coop/engineering/architecture/rfcs/
-->

## Overview

### Title
<!-- A clear, descriptive title for the proposal -->

### Category
<!-- Select the primary category -->
- [ ] Public interfaces (contracts and boundaries)
- [ ] Features (new functionality or capabilities)
- [ ] Protocols (communication standards and formats)
- [ ] Behaviour (how the system responds or operates)
- [ ] Community process (governance and workflows)
- [ ] Standards (public specifications and conventions)

### Affected projects
<!-- Which Rai Vision projects does this proposal affect? -->
- [ ] Observability core (metric collection, trace aggregation, log ingestion)
- [ ] Dashboards (data visualisation, interactive exploration, alerting)
- [ ] Analysis (anomaly detection, trend analysis, reporting)
- [ ] Integrations (Shield telemetry, Arai agent monitoring, Prism experiment tracking)
- [ ] Data pipeline (stream processing, storage backends, retention policies)
- [ ] Deployment (standalone server, containers, embedded mode)
- [ ] Other: <!-- specify -->

---

## Summary

### Proposal
<!-- One paragraph summary of what you are proposing -->

### Motivation
<!-- Why is this change needed? What problem does it solve? -->

---

## Impact

### Who is affected?
<!-- Who will be affected by this change and how? -->

### Migration considerations
<!-- Will existing setups need to change? -->

---

## Proposed design

### Overview
<!-- High-level description of the proposed solution -->

### Alternatives considered
<!-- Briefly list other approaches you considered -->

---

## Discussion

### Open questions
<!-- Questions that need community input -->
- <!-- Question 1 -->
- <!-- Question 2 -->

### Discussion period
**Proposed duration**: <!-- minimum 14 days -->

---

## Next steps

- [ ] Draft full proposal in `rfcs/XXXX-title.md`
- [ ] Submit merge request to begin discussion period
- [ ] Engage with community feedback
- [ ] Await decision after discussion closes

---

## Governance

This proposal follows the
[Omnifi Foundation governance model](https://handbook.omnifi.coop/engineering/architecture/governance/).
Technical leads carry responsibility for facilitating decisions after the
community discussion period closes. See the
[handbook](https://handbook.omnifi.coop/engineering/architecture/rfcs/) for
process details.

/label ~"rfc" ~"architecture" ~"needs discussion"
