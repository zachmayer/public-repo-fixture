# H2 2026 Platform Roadmap Summary

## Overview
Platform roadmap for H2 2026 focused on three core themes: **reliability**, **search quality**, and **on-device AI**.

## Q3 2026 Initiatives

- **Ranking Service Migration** (Platform) — Migrate ranking service to new feature store. Target: August
- **On-Device Summarization Beta** (Apps/AI) — Roll out to 5% user base. Target: September
- **Autocomplete Latency Improvement** (Search Infra) — Reduce p99 latency by 20%

## Q4 2026 Initiatives

- **Summarization General Availability** (Apps/AI) — Full release of summarization feature
- **Multi-Region Failover** (SRE) — Implement failover for query pipeline across regions
- **Legacy Index Deprecation** (Search Infra) — Deprecate index shards v3

## Dependencies & Constraints

- Feature-store migration is a blocking dependency for summarization GA
- SRE team has a staffing gap with 2 open requisitions impacting failover timeline
