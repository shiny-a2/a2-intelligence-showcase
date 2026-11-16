# A2 Intelligence — engineering showcase

A2 Intelligence is an isolated, Persian-first assistant platform experiment. Its web app and shared conversation engine are designed for several channels, with tenant-scoped identity, usage limits, and reviewed administration workflows.

## Proposal inbox and safe decisions · 2026-11-17 candidate

The shared platform now lists a manager's currently authorized proposals and supports explicit rejection or dismissal before execution. Competing confirmation and dismissal have one durable winner. Dismissal cannot cancel completed, running or uncertain work. Completed receipts remain reviewable after the approval deadline, while expired pending proposals cannot execute, including after waiting for a database lock.

The build and 83 isolated tests passed, plus 20 focused checks and seven final lifecycle checks. Tests used encrypted database receipts, real row contention and the shared HTTP SDK with scripted product effects. The unchanged Beauty connection passed 13 local compatibility checks. A bounded inbox query used its intended index in a disposable 20,000-row metadata fixture. No paid model or production action occurred.

This is central service and SDK progress. The Beauty inbox screen and current CRM write integration still need to be connected and verified; existing Beauty remains on its read-only source candidate. Historical access is not expanded across authority changes. Production activation and uncertain-outcome reconciliation remain open.

## Inspect saved assistant results · 2026-11-17 candidate

The shared platform now exposes read-only request status without executing tools, calling a model or recording another model charge. Current identity, scope and assistant policy are rechecked before returning a saved result. Pending remains explicitly uncertain; it is not a promise that work is running in the background. Existing product integrations retain their established message and approval contracts.

Beauty consumes this capability in an enabled-only daily workbench card with explicit request, check and continuation controls. The central build and 76 tests passed; the consumer build and 425 tests passed, followed by 57 responsive interactive checks and four logout regressions. Scripted model output and local synthetic data were used throughout. No paid provider or production activation occurred. Mixed write recovery, uncertain-provider reconciliation and production provisioning remain open.

## Durable read-only recovery · 2026-11-17 candidate

The shared agent now saves encrypted report checkpoints before continuing model work and stores the completed answer before delivery. Repeating the same request recovers the original reports or final answer with fresh access and policy checks. Expiry clears private payloads while retaining the duplicate-request guard. The existing model engine and usage ledger still own provider calls and charging.

The central build and all 75 isolated tests passed; six final recovery checks also passed after adding access revocation during replay. Tests used real local storage and usage receipts with scripted model output, including a fresh process, lost responses, concurrent retries, changed input, revoked access and expiry. The Beauty consumer build and 424 tests passed. No paid model or production activation occurred. This covers read-only conversations; mixed read/write recovery, uncertain provider reconciliation and production provisioning remain open.

## Beauty daily-workbench connection · 2026-11-17 candidate

The central catalogue now supports a read-only Beauty workbench summary through the existing shared agent engine and HTTP SDK. The product rechecks current salon and staff access, binds any selected CRM line to a short-lived delegation and returns a compact report without customer names or contact details. Appointment counts and CRM preview sizes are explicitly distinguished. No second model engine, business data store or write capability was introduced.

The central build and 69 isolated database/contract tests passed, followed by 13 focused agent checks. The Beauty consumer passed its build and 424 tests; its final 12-check integration run exercised the actual SDK, central HTTP/agent stack and canonical database reader with synthetic model and policy ports. Forged scopes, expired delegation, revoked sessions, disallowed model actions and malformed replies fail closed. No paid model or production deployment was used.

This connection remains disabled. The later recovery candidate above addresses read-only report replay; exact production entitlement/budget provisioning and a manager-facing interface are still open. At this earlier baseline, a changed report under the same operation key returned an explicit conflict without silently starting another paid request. Existing product assistance continues on its established path; source publication does not activate a general operational agent.

## Central agent tool catalogue · 2026-11-05

The shared agent candidate now defines the descriptions, input shapes and product permission bindings for its CRM tools in one central A2 Intelligence catalogue. Beauty and Education advertise their available capability names; each product still checks the current user's authority and executes its own business records. Unknown or altered tool contracts are denied. This gives future products, including Learning, a single reviewed place to register tools while keeping their own domain data and permissions.

The Intelligence build and 12 focused tests passed. The corresponding Beauty adapter passed 301 tests, and the Education adapter passed 14 synthetic demo checks. These are private source candidates, not activated shared agents. Learning's separate connection has not been verified here. The active limited Beauty demo secretary continues on its existing capped service; Beauty 0.30.6 improved its appointment suggestions and photo-review notice without activating the generic agent. Production entitlement, scoped runtime binding and recovery checks remain open before a shared rollout.

## Shared business agent candidate · 2026-11-04

Education and Beauty now have a locally tested shared text-agent candidate. It reads authorized CRM reports, finds relevant records and proposes internal follow-up creation or completion. A proposal changes no business record until the current manager confirms the exact action; repeated confirmation reuses the recorded result. Student/customer guidance and manager tools share the existing assistant engine and provider routing.

Validation used disposable databases and scripted model output: 67 shared-platform tests, 31 focused Beauty regressions, 14 Education regressions and 15 cross-product integration checks passed. Eight mobile/desktop light/dark browser scenarios exercised reports, readable proposals, keyboard focus and completed states, with no page exceptions or horizontal overflow.

**Status:** private source candidate, disabled by default; not a live shared-agent release. Existing Beauty photo/booking assistance is preserved pending its explicit compatibility migration. Production access and runtime activation, durable chat, an approval inbox and scheduled reports remain open. This work made no paid model request or production deployment.

## One central AI foundation

Chatbot behavior, business profiles, knowledge and memory, agent planning/tools, provider routing and AI cost/budget management are owned by the central A2 assistant platform. Education, Beauty and future products consume it through authorized business adapters. Remaining legacy paths and product-local policy copies are consolidation work; they are not separate AI development tracks. This is the architecture decision, not a claim that migration or live activation is complete.

## Phase 1Q isolated identity update · 2026-10-19

- Prepared one administrator sign-in tied to the existing owner identity, with an initial password change and two-step verification before privileged use.
- Built a disabled-by-default standards-based sign-in pilot for future A2 products. Product-specific connections remain separate work and are not presented as live SSO.
- Added explicit, time-limited product access checks and a clearer environment and workspace label in the administrator interface.
- Passed 51 isolated database tests and synthetic browser checks for the first sign-in across mobile and desktop in both light and dark themes.

**Status:** private source candidate only. The active development preview was not updated because the real owner has not completed two-step enrollment and release backup checks remain open. Sensitive changes still require independent review or a documented emergency process. No customer-panel access, paid provider, staging or production rollout was added.

## Phase 1P isolated security update · 2026-10-18

- Prepared a guided two-step sign-in enrollment path for the private development administrator and tightened sensitive approval and publication checks.
- Made pending changes visible to reviewers with limited permissions while keeping editing and self-approval separate.
- Validated 48 isolated database tests and real-backend synthetic browser sign-in flows across mobile and desktop, light and dark themes.
- Added a synthetic two-administrator browser run for reviewed assistant changes, rollback and invitations. A read-only DEV check confirmed that the human enrollment gates remain unmet.

**Status:** source changes are in private development. The current private preview has not been updated because administrator enrollment and a second authorized human reviewer remain outstanding. No customer access, paid AI, staging or production rollout was added.

## Phase 1O isolated update · 2026-10-18

- Added a clearer review sequence for assistant configuration: draft, submit, independent approval, publication and reviewable rollback.
- Added a separate draft, submit, independent approval and publication sequence for synthetic identity changes, with a reviewed reversal path for reversible changes.
- Prepared an optional server-side AI provider adapter and an extension point for external workers; both were tested with synthetic responses. The live private preview still uses the fake provider; no paid provider request or real credential was used.
- Passed 47 isolated tests against disposable PostgreSQL and reviewed responsive admin, identity and chat screens in light and dark themes. Corrected a mobile navigation visibility issue.

**Status:** source and reports are in private development. The existing restricted preview remains on its previous release while independent administrator and accessibility gates are completed. No staging or production rollout occurred.

## Phase 1N update · 2026-10-18

- Redesigned the Persian chat and administration preview around one responsive light/dark design system, clearer navigation, measured development indicators and contextual help.
- Added guided administrative drafts and an eight-step assistant setup flow while retaining independent review and audit before activation.
- Added tenant-scoped branding configuration and improved chat history, streaming feedback, offline state and mobile layouts.
- Validated synthetic browser flows across phone, tablet and desktop layouts, then checked the restricted live development preview on phone and desktop. An integration permission issue found during live checking was corrected within development.
- Added the existing IRANYekan font after the owner confirmed its A2 license. Confirmed actual font loading and layout in the restricted preview at phone, tablet and desktop widths, in light and dark themes.

**Status:** restricted development preview only. The licensed font stays in private source and is not published in this showcase. Production authentication, external AI providers, customer data, staging and production deployment are outside this update.

## Phase 1M update · 2026-10-18

- Opened a credential-gated private preview of the Persian chat PWA and administration dashboard on an isolated development runtime.
- Simplified owner access to one account credential for the private development preview; live sign-in and administrator access were checked.
- Corrected enrollment throttling behind the proxy and verified the private preview access flow with synthetic checks.
- Tested synthetic chat, conversation history, private administration and responsive light/dark layouts. Improved mobile table navigation and handled rapid admin navigation safely.
- Rechecked encrypted development backup restoration and kept production services and customer data separate.

**Status:** private development preview only. The convenience sign-in is limited to this environment; stronger production authentication remains a separate release gate. Public registration, paid AI, bot activation, independent staging and production deployment remain outside this release. No access credentials or private infrastructure details are published here.

## Phase 1L update · 2026-10-18

- Provisioned a private development environment after checking host identity and resource capacity. Its chat app uses synthetic accounts and a fake AI provider and is accessible only through a restricted local connection.
- Validated browser layouts in light and dark themes at mobile and desktop widths, plus conversation history, streaming recovery, tenant separation, sign-in safeguards and usage limits.
- Verified encrypted development backup restoration and migration rollback in disposable databases. Resource caps and monitoring checks protect existing workloads.

**Status:** controlled development use only. Public access, independent staging and production deployment remain pending separate readiness gates. No real AI credentials, customer records or bot integrations were used.

## Phase 1K correction · 2026-10-18

- Corrected an earlier infrastructure identity error: prior high-load measurements and a provider response test were attributed to the wrong host. They must not be used as evidence for the A2 Central server.
- Rechecked the actual A2 host with read-only measurements. Its current CPU and memory load is low; a larger host may still be needed for four new isolated environments.
- Recorded separate capacity, backup, database and web-service findings, plus a safe handoff for the other host.

**Status:** no infrastructure or application changes were made. The capacity upgrade remains a planning decision requiring load testing and separate approval.

## Phase 1J update · 2026-10-18

- Reviewed host capacity and proposed separate development, staging, demo and production boundaries.
- Added an offline deployment preflight that rejects mismatched environment identities and state references.
- Confirmed that the shared assistant engine still uses a fake provider in isolated tests; real-provider operations require separate eligibility and release gates.
- Documented a shared PWA, central administration and optional Telegram integration path.

**Status:** the current host does not meet the capacity gate for all four environments. No environment was provisioned, and no live application or bot was changed.

## Phase 1I update · 2026-10-18

- Completed a read-only infrastructure review and proposed an independent staging environment.
- Pinned source releases and prepared checks for TLS, backup restoration, queue recovery and accessibility.
- Validated provider connectivity boundaries and kept real-provider access subject to location and account eligibility.
- Confirmed the current direct network path separately from any authenticated provider test.
- Completed one minimal direct provider response test after owner-reported approval; deployment eligibility remains under review.

**Status:** planning and verification only. No staging infrastructure or application was deployed. Public notes contain no host addresses, credentials, customer data or private configuration.

## Phase 1H update · 2026-10-18

- Added an isolated, authenticated licensing link and tested signed revocation delivery, retry and tenant separation.
- Added reviewed identity administration, one-time account recovery with a test delivery adapter, and key rotation controls.
- Exercised the PWA against isolated backend services in light and dark themes at mobile and desktop widths.
- Recorded deployment gates for independent staging, including secrets, monitoring, recovery and accessibility.

**Status:** isolated engineering validation. Independent staging and production deployment are not approved. No customer information, credentials or private infrastructure is included here.

## Phase 1G update · 2026-10-18

- Validated a signed licensing contract across PHP and TypeScript with synthetic fixtures.
- Added isolated central web login flows for two-step verification and account recovery.
- Tested tenant boundaries, revocation, browser layouts and rollback in local environments.

**Status:** isolated engineering validation. Operational integration and staging deployment remain pending. This public summary contains no source code, customer data, credentials or private infrastructure details.

## Phase 1F update · 2026-10-18

- Prepared a standalone identity foundation with revocable sessions and delegated, signed user assertions.
- Defined a versioned, signed licensing contract with explicit product, assistant, subscription, and quota scope.
- Connected reviewed administrative changes to active isolated runtime configuration, including version history and rollback.
- Expanded local checks for revocation, concurrent publication, migration rollback, and responsive PWA behavior.

**Status:** isolated engineering validation. Staging and production rollout remain pending. This showcase contains no customer data, credentials, source code, or private infrastructure details.
