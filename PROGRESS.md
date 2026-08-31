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
- DATA-COST-CACHE--resilience: sub-feature discussion completed - storage reliability/failure-handling
- DATA-COST-CACHE--cost-admin: sub-feature discussion completed - platform cost-monitoring/guardrail design
- DATA-COST-CACHE--semantic-cache: sub-feature discussion completed - content reuse strategy
- DATA-COST-CACHE: feature fully documented (parent + all sub-features)
- Process fix: specialist-agent proposals now require explicit user confirmation before being recorded as decided
- DATA-COST-CACHE: a tuning parameter revised after further review
- DATA-COST-CACHE: core storage-technology decision reconsidered and reversed, following external review
- DATA-COST-CACHE: architecture, data-model and technology docs rewritten to match the reversed storage decision
- DATA-COST-CACHE: a caching-technology re-evaluation and a rejected reliability proposal recorded from external review

## 2026-07-23
- FRONTEND: initial feature discussion completed - client application architecture and page structure
- FRONTEND: lean parent feature file written; sub-feature list drafted
- FRONTEND--architecture: sub-feature discussion completed - internal application structure and integration seams
- Process cleanup: FRONTEND--architecture re-scoped to structural-only content, mechanism/tech detail deferred to their own sub-features
- FRONTEND--technologies: sub-feature discussion completed - client application technology-stack decision
- FRONTEND--state-data: sub-feature discussion completed - client state-management and data-fetching design

## 2026-07-26
- Process addition: shared cross-feature value registry (Contracts/) scaffold created
- Process: bootstrap cross-feature consistency review run across existing documented features, findings recorded for later resolution
- FRONTEND--auth-communication: sub-feature discussion completed - authentication flow and backend-communication design
- FRONTEND--pages: sub-feature discussion completed - page inventory and navigation/access design
- FRONTEND--playback-interaction: sub-feature discussion completed - event-card interaction and pacing design
- DYNAMIC-VISUALS--lifecycle: playback pacing rule clarified (cross-feature amendment)
- FRONTEND--responsive: sub-feature discussion completed - mobile/tablet/desktop layout strategy (all component sub-features now done)

## 2026-08-12
- FRONTEND--caching: in-progress data-refresh/recovery mechanism decision locked (small cross-amendment to FRONTEND--state-data)

## 2026-08-18
- FRONTEND--caching: sub-feature discussion completed - client-side data caching/refresh strategy
- FRONTEND--state-data: streaming-progress storage mechanism amended (cross-feature amendment)
- FRONTEND--security: in-progress - AI-generated content rendering safety decision locked
- DATA-COST-CACHE--data-model: storage-placement rationale for one content type revisited and re-confirmed (cross-feature question)
- FRONTEND--security: in-progress - client-side data exposure review completed, API response and build-config hardening decisions locked
- FRONTEND--security: sub-feature discussion completed - client threat model, AI-content rendering, and dependency-hardening strategy (all 5 default sub-features now done, only --resilience remains for FRONTEND)

## 2026-08-29
- FRONTEND--playback-interaction: playback pacing model revisited and reversed (cross-feature amendment, DYNAMIC-VISUALS--lifecycle)
- Process addition: full-pipeline reference diagram created (master system map + one sheet per major piece, with a numbered failure-mode legend)
- FRONTEND--resilience: sub-feature discussion completed - client failure-handling and degradation strategy (FRONTEND now fully documented, 10/10 sub-features)

## 2026-08-30
- Process addition: pipeline reference diagram refined - rendering accuracy fixes and new resilience content
- Process addition: two new features added to project scope - outbound notifications, visual/motion design
- SOCIAL-SHARING: initial feature discussion completed - social graph and discovery design (2 of 7 sub-features written)
- SOCIAL-SHARING--resilience: sub-feature discussion completed - operational failure-handling strategy
- SOCIAL-SHARING--security: sub-feature discussion completed - threat-model and abuse-vector review (with amendments to --social-graph and --discovery)
- SOCIAL-SHARING: feature fully documented - architecture, technology stack, and caching strategy locked (7/7 sub-features)
- Process addition: pipeline reference diagram extended with the new feature; visual HTML recap built for the new feature

## 2026-08-31
- DATA-COST-CACHE--data-model: persistence schema amended following an independent verification pass; entity-relationship map added (cross-feature amendments to SOCIAL-SHARING, FRONTEND, BACKEND-API)
- BACKEND-API--api-surface: a pre-existing status-model gap identified and flagged for a future pass
- BACKEND-API--auth, FRONTEND--auth-communication, FRONTEND--pages: an additional sign-in mechanism adopted and its client-side flow locked (additive amendments; one open item flagged)
- DATA-COST-CACHE--data-model: two parts of the same-day schema amendment revised after further discussion - one reverted, one restructured and renamed (ripples to BACKEND-API, DATA-COST-CACHE--architecture)
