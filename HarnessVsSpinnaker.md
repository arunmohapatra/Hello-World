
Top 10 Harness CD Features Missing in Spinnaker

1. SaaS Platform (No Infra Burden)
Harness offers a fully managed SaaS control plane — no need to install or maintain the core CD system.
Spinnaker requires you to run and maintain the whole platform yourself.

2. Delegate Model (Lightweight Agent)
Harness uses a Delegate (single agent in your infra) that securely connects back to Harness SaaS.
Spinnaker requires a large set of microservices (Clouddriver, Orca, Gate, etc.), making it heavy to deploy and manage.

3. Built-in GitOps Support
Harness pipelines, services, and environments can be fully synced with Git (GitOps-first approach).
Spinnaker needs plugins or custom integration for GitOps workflows.

4. AI/ML-driven Auto Rollbacks
Harness continuously monitors logs, metrics, error rates (via ELK, Prometheus, Datadog, etc.).
It can auto-trigger a rollback when anomalies are detected.
Spinnaker does not have native AI/ML analysis for automated rollback.

5. Continuous Verification (CV)
Harness has a built-in CV module that automatically verifies deployments against monitoring tools.
Provides automated canary/baseline checks.
Spinnaker has canaries but relies on Kayenta (extra setup, less integrated).

6. Integrated Feature Flags
Harness combines progressive delivery (canary, blue/green) with feature flags in the same platform.
This allows true safe deployments.
Spinnaker has no native feature flagging system.

7. Cost Awareness in Pipelines
Harness integrates cloud cost visibility into CD.
Lets you see what each deployment costs and optimize.
Spinnaker has no cost management capability.

8. Security & Compliance (SSCA)
Harness CD integrates with SSCA (Software Supply Chain Assurance).
Includes artifact provenance, license checks, and vulnerability scans before deployment.
Spinnaker does not offer integrated SSCA — you need external tools.

9. Simple Canary / Blue-Green without Extra Setup
Harness natively supports canary, blue/green, and rolling updates with automatic traffic shifting.
In Spinnaker, advanced strategies often need Kayenta, Istio, or extra setup.

10. Unified Platform (One UI, One Config)
Harness brings CI, CD, Feature Flags, Chaos, SRM, CCM, SSCA into one platform.
Even for CD alone, you get security, verification, cost, approvals, audit trails in one place.

Spinnaker focuses only on CD, so you must integrate multiple external tools.

✅ Summary (One-Liner Per Benefit)

SaaS (no infra headaches)

Lightweight delegate vs microservices

Native GitOps

AI/ML auto rollbacks

Continuous Verification module

Built-in Feature Flags

Deployment cost visibility

Supply Chain Security (SSCA)

Simple canary/blue-green support

Unified platform beyond CD
