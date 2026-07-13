# Progress Log

Sanitized, public-safe record of when design and architecture work happened on this project. Entries name the feature and the general topic of what was decided or completed - never the actual resolution, chosen technology, or rationale. Full detail lives in the private (gitignored) vault and `.claude/issues/`.


## 2026-06-25
- DYNAMIC-VISUALS--visual-bundle: sub-feature discussion completed - content pipeline design
- DYNAMIC-VISUALS--globe: sub-feature discussion completed - interactive map/globe composition logic
- DYNAMIC-VISUALS--technologies: sub-feature discussion completed - visualization technology-stack decision
- DYNAMIC-VISUALS--caching: sub-feature discussion completed - visual-generation cost/caching levers
- DYNAMIC-VISUALS: threat-model sub-feature discussion completed - threat model
- AGENT-ENGINE--events: sub-feature discussion completed - output data-model design

## 2026-07-01
- BACKEND-API: initial transport/coordination design completed (later archived)

## 2026-07-02
- AGENT-ENGINE--technologies: sub-feature discussion completed - engine technology-stack decision
- DYNAMIC-VISUALS: security sub-feature consolidated into a single file - threat model
- BACKEND-API--technologies: sub-feature discussion completed - backend technology-stack decision

## 2026-07-03
- BACKEND-API: hosting/execution model decided
- BACKEND-API--auth: sub-feature discussion completed - authentication/authorization design
- BACKEND-API--caching: sub-feature discussion completed - backend caching-layer strategy
- BACKEND-API--security: sub-feature discussion completed - access-control/auth threat model
- BACKEND-API: sub-feature list locked; data ownership boundary clarified

## 2026-07-04
- BACKEND-API: coordination-layer mechanism designed in depth

## 2026-07-06
- ACCOUNTS-TIERS-BILLING--accounts: sub-feature discussion completed - user identity/account record design
- ACCOUNTS-TIERS-BILLING--quota: sub-feature discussion completed - usage-quota accounting design
- ACCOUNTS-TIERS-BILLING--moderation: sub-feature discussion completed - content moderation policy/gate design
- ACCOUNTS-TIERS-BILLING--architecture: sub-feature discussion completed - system placement of the membership feature
- ACCOUNTS-TIERS-BILLING--technologies: sub-feature discussion completed - accounts/billing vendor-stack decision
- ACCOUNTS-TIERS-BILLING--caching: sub-feature discussion completed - membership-rules caching strategy
- ACCOUNTS-TIERS-BILLING--security: sub-feature discussion completed - threat model for accounts/billing/entitlements

## 2026-07-07
- DYNAMIC-VISUALS--resilience: sub-feature discussion completed - failure/degradation handling for visual generation
- DYNAMIC-VISUALS: feature fully documented (parent + all sub-features)
- ACCOUNTS-TIERS-BILLING: feature fully documented (parent)
- Convention: per-feature visual summary page introduced

## 2026-07-08
- Convention: summary pages required to include a dedicated security section
- BACKEND-API: major architectural pivot - transport & coordination model simplified; prior design archived as reference

## 2026-07-10
- AGENT-ENGINE--architecture: sub-feature discussion completed - internal component layering and engine boundary
- DYNAMIC-VISUALS--lifecycle: sub-feature discussion completed - playback behavior design
- ACCOUNTS-TIERS-BILLING--tiers: sub-feature discussion completed - membership-tier/entitlement model
- BACKEND-API--architecture: sub-feature discussion completed (revised post-pivot) - request-handling and system-boundary design
- AGENT-ENGINE--era-stepping: sub-feature discussion completed - timeline progression and step-granularity mechanics
- DYNAMIC-VISUALS--architecture: sub-feature discussion completed - content pipeline design
- AGENT-ENGINE--carry-forward: sub-feature discussion completed - cross-step state continuity design
- DYNAMIC-VISUALS--grapher: sub-feature discussion completed - visual generation design
- AGENT-ENGINE--caching: sub-feature discussion completed - per-run cost-reduction levers
- Convention: a mandatory security sub-topic added for every feature, backfilled into already-documented features
- AGENT-ENGINE--security: sub-feature discussion completed - threat model and injection/trust surfaces
- AGENT-ENGINE: feature fully documented (parent + core sub-features)
- BACKEND-API--api-surface: sub-feature discussion completed - public API endpoint catalog/contract

## 2026-07-11
- BACKEND-API--run-lifecycle: sub-feature discussion completed - per-request execution lifecycle
- BACKEND-API--streaming: sub-feature discussion completed - response-streaming transport design
- Convention: a mandatory resilience sub-topic added for every feature, backfilled into already-documented features
- AGENT-ENGINE--communication: sub-feature discussion completed - inter-agent coordination pattern
- AGENT-ENGINE--engine-run: sub-feature discussion completed - execution contract and run-control ownership
- AGENT-ENGINE--resilience: sub-feature discussion completed - failure-handling and degradation strategy
- ACCOUNTS-TIERS-BILLING--billing: sub-feature discussion completed - payment-processing integration design
- ACCOUNTS-TIERS-BILLING--byo-keys: sub-feature discussion completed - user-supplied credential registry design
- ACCOUNTS-TIERS-BILLING--resilience: sub-feature discussion completed - failure-handling for billing/quota/key flows
- BACKEND-API: identity-token contents revised (self-correction)
- BACKEND-API--resilience: sub-feature discussion completed - failure-handling and recovery mechanics
- BACKEND-API: crash-recovery timing mechanism corrected after a walkthrough caught a bug
- Process cleanup: failure-handling documentation de-duplicated across multiple features into one canonical location
- DATA-COST-CACHE--precompute: sub-feature discussion completed - precomputation strategy

## 2026-07-14
- DATA-COST-CACHE: feature scope + storage topology decided
- DATA-COST-CACHE--architecture: sub-feature discussion completed - data-storage topology/placement design
- DATA-COST-CACHE--data-model: sub-feature discussion completed - persistent schema design
- DATA-COST-CACHE--technologies: sub-feature discussion completed - storage technology-stack decision
- DATA-COST-CACHE--caching: sub-feature discussion completed - cross-cutting caching-ladder strategy
- DATA-COST-CACHE--security: sub-feature discussion completed - storage-layer threat model
