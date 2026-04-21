import { useState } from "react";

const categories = {
  "Opening & Narrative": "#e8f4fd",
  "Behavioral": "#f0fdf4",
  "Product Thinking": "#fdf4ff",
  "Technical & Domain": "#fff7ed",
  "Stakeholder & Strategy": "#fef2f2",
  "Closing": "#f0f9ff",
};

const categoryColors = {
  "Opening & Narrative": { bg: "#1a4a6b", accent: "#3b9edd", light: "#e8f4fd", tag: "#d0eaf8" },
  "Behavioral": { bg: "#14532d", accent: "#22c55e", light: "#f0fdf4", tag: "#bbf7d0" },
  "Product Thinking": { bg: "#581c87", accent: "#a855f7", light: "#fdf4ff", tag: "#e9d5ff" },
  "Technical & Domain": { bg: "#7c2d12", accent: "#f97316", light: "#fff7ed", tag: "#fed7aa" },
  "Stakeholder & Strategy": { bg: "#7f1d1d", accent: "#ef4444", light: "#fef2f2", tag: "#fecaca" },
  "Closing": { bg: "#0c4a6e", accent: "#06b6d4", light: "#f0f9ff", tag: "#bae6fd" },
};

const questions = [
  {
    id: 1,
    category: "Opening & Narrative",
    difficulty: "High",
    mustKnow: true,
    question: "Walk me through your background and tell me — why Teradata, and why this role specifically?",
    answer: `Start with the connective thread, not a chronological resume dump.

"I'm a product manager with two and a half years across B2B SaaS, e-commerce, and EdTech — and the through-line across all of it is sitting between data and decision. At Enigma Metaverse, I deployed Pega's Customer Decision Hub to build a predictive churn model that moved our retention strategy from reactive firefighting to proactive intervention. At Aasaan App, I built an ML lead-scoring model in Python that lifted sales efficiency by 46% — not by adding headcount, but by making the signal better. That's ClearScape's philosophy in miniature.

What draws me to Teradata specifically is that you're solving the hardest version of the analytics problem: not just running a model, but governing it, operationalizing it, and doing it at petabyte scale across enterprise environments where failure is expensive. The Forrester study — 244% ROI, $125M in profits — that's the outcome of getting this right. I want to contribute to building that. And I want to learn it from a team that's already doing it at this level."

Why it works: You mirror her language (operationalizing, governance, scale), show you've done real research, and frame your past work as direct evidence for the future.`,
    tip: "Dr. Vouk is VP-level. She's heard hundreds of 'I'm passionate about AI' openers. What she respects is specificity and evidence.",
  },
  {
    id: 2,
    category: "Opening & Narrative",
    difficulty: "Medium",
    mustKnow: true,
    question: "How do your past roles connect to what this APM role requires?",
    answer: `Bridge every past experience to a specific JD requirement.

"Let me map it directly. The JD asks for experience drafting PRDs and user stories — at Enigma, I wrote acceptance criteria for every user story before developer handoff across 6+ engineering cycles, cutting sprint rework by 38%. The JD asks for competitive research — at Aasaan, I ran SWOT analysis that realigned our GTM to actual buyer pain points, delivering a 16% CVR improvement. The JD asks for tracking product usage and gathering customer feedback — at Aasaan, I ran funnel decomposition across acquisition, activation, and revenue cohorts and turned those findings into roadmap inputs that reduced churn by 21.8%.

The only area where this role stretches me is the depth of enterprise analytics platform knowledge. ClearScape Analytics, VantageCloud, ModelOps — I've been deliberately studying these, and I came into this conversation prepared to discuss them at a technical level. That's the gap I'm closing in real time, and based on past pattern, I close gaps quickly."

Why it works: You don't just claim fit — you prove it, line by line. And you name the gap before she does, which builds trust.`,
    tip: "Never leave Dr. Vouk to infer the connection. Make it explicit. She's a systems thinker — she'll appreciate the mapping.",
  },
  {
    id: 3,
    category: "Behavioral",
    difficulty: "High",
    mustKnow: true,
    question: "Tell me about a time you translated complex technical output into something a business stakeholder could act on.",
    answer: `STAR: Situation → Task → Action → Result

Situation: At Aasaan App, I built an ML lead-scoring model that classified inbound leads by conversion probability. The model performed well on validation data. The problem wasn't the model — it was adoption.

Task: The sales team was skeptical of a 'black box' telling them which leads to prioritize. My job was to earn that trust without a weeks-long training program.

Action: I ran a two-week shadow period. I overlaid model scores against rep intuition and tracked outcomes in parallel. Then I brought a simple comparison to the team: 'Here are the 20 leads the model flagged in week one. Here's how they converted versus your picks.' Conversion on model-flagged leads was 2.3x higher. I showed them the features driving the score — not in statistical terms, but in their language: 'leads from companies with 10-50 employees who've viewed pricing page 3+ times are your highest-value segment.'

Result: The team adopted the scoring within a month — no mandate, just evidence. Sales efficiency lifted 46%.

The meta-lesson I draw from this: the model is 40% of the job. The product experience around the model — explanation, trust-building, interface design — is the other 60%. That's directly applicable to ClearScape's AutoML and ModelOps adoption challenge.`,
    tip: "This is the question Dr. Vouk will care most about. She spent years at IBM getting enterprises to trust AI. This answer shows you understand the human side of AI adoption.",
  },
  {
    id: 4,
    category: "Behavioral",
    difficulty: "High",
    mustKnow: true,
    question: "Describe a time you managed multiple competing stakeholder priorities simultaneously. How did you resolve the conflict?",
    answer: `STAR format with emphasis on process and outcome.

Situation: At Enigma Metaverse, I was leading the Community v1 product — a community engagement feature — with a cross-functional team that had no prior history of working together. Design had an ambitious UX vision. Legal was concerned about content moderation liability. Business had revenue expectations tied to a launch date. Engineering had capacity constraints from a parallel initiative.

Task: I needed to ship in 3 sprints without mid-sprint scope changes — which had plagued previous launches.

Action: I ran structured 1:1 stakeholder interviews in week one. The key question I asked each stakeholder: 'What does success look like for you, and what would cause you to say this failed?' Then I synthesized the answers into a prioritized feature backlog with explicit trade-off documentation — every item had a rationale for inclusion, an owner, a success metric, and a note on what it displaced. I held a single alignment session where I walked through the backlog and asked for explicit sign-off, not consensus.

Result: We shipped Community v1 in 3 sprints with zero mid-sprint scope changes. Legal's concerns were addressed in the design review before development started. The launch hit the business timeline.

What I'd bring here: the same discipline of structured input gathering + transparent trade-off documentation that makes cross-functional work executable rather than collaborative in name only.`,
    tip: "Notice the answer names the process explicitly. Dr. Vouk will be thinking 'can this person do this for my senior PMs at scale?' Show you have a repeatable method.",
  },
  {
    id: 5,
    category: "Behavioral",
    difficulty: "Medium",
    mustKnow: false,
    question: "Tell me about a time you used data to challenge an existing assumption or change a team's direction.",
    answer: `STAR with a clear narrative arc.

Situation: At Aasaan App, the growth team's working assumption was that acquisition was our bottleneck. More leads = more revenue. We were investing heavily in top-of-funnel campaigns.

Task: I was asked to do a funnel review. What I found was unexpected.

Action: I ran a full AARRR decomposition — Acquisition, Activation, Retention, Revenue, Referral — across three months of cohort data. Activation rate was actually above benchmark. The problem was retention: we were losing users at day 14 at nearly double the rate of comparable B2B SaaS products. I traced the root cause to a feature gap — merchants couldn't integrate their existing inventory systems without developer support, which most of our SMB customers didn't have. I documented this with cohort data and support ticket analysis, quantified the revenue impact of the retention gap versus the marginal return of additional acquisition spend, and brought it to the product team with a specific feature recommendation.

Result: The integration feature became one of three Q3 roadmap priorities. Churn dropped 21.8% in the following period. The growth team reallocated campaign budget and saw better return.

The principle: don't just answer the question you were asked. Look for the question that actually matters. That's the difference between a good analyst and a good product thinker.`,
    tip: "This answer demonstrates analytical courage — you challenged a senior team's direction with data. That's rare and memorable.",
  },
  {
    id: 6,
    category: "Behavioral",
    difficulty: "Medium",
    mustKnow: false,
    question: "Describe a situation where you had to learn something complex quickly. How did you approach it?",
    answer: `Show a repeatable learning method — not just a one-time story.

Situation: At Aasaan App, I was tasked with building an ML lead-scoring model. I had working Python knowledge but had never built a production classification model end-to-end. I had three weeks before the sales team needed something usable.

Task: Not just to build the model — but to make it trusted and adopted.

Action: I treated it like a product sprint with a defined acceptance criterion: what accuracy threshold would make the sales team act on the output? I worked backwards from that. I used scikit-learn, tested logistic regression and decision tree variants, validated on holdout data, and built a CSV export interface so the team didn't need to touch code. I shared progress weekly with the sales lead, incorporating their feedback on feature interpretation into the model's explanation layer.

Result: 46% sales efficiency lift. More importantly, full adoption within a month.

The learning pattern I use in any domain: define what 'good enough to be useful' looks like, build iteratively with the actual user, and validate at each stage. I've applied this to getting up to speed on ClearScape Analytics, ModelOps architecture, and Teradata's agentic AI roadmap ahead of this conversation — because I wanted to have a real discussion, not a surface-level one.`,
    tip: "End with the meta-point about your preparation for THIS interview. It shows the same learning behavior in action, right now.",
  },
  {
    id: 7,
    category: "Behavioral",
    difficulty: "High",
    mustKnow: false,
    question: "Have you ever disagreed with a senior stakeholder's decision? What did you do?",
    answer: `This is a values and judgment question disguised as a behavioral one.

Situation: At Enigma Metaverse, a senior stakeholder wanted to prioritize a feature based on strong advocacy from one enterprise client. It was loud, it was urgent, and they were a high-value account.

My concern: our cohort data showed this client was an outlier. The feature wouldn't serve the broader user base and would consume roughly 40% of one sprint's engineering capacity.

What I did: I didn't push back in the room. Instead, I came back within 24 hours with structured data — usage patterns across our top 10 accounts, frequency ranking of this request versus other items in the backlog, and a clear opportunity cost frame: 'Here's what we'd trade off to build this now versus Q3.' I presented it privately to the stakeholder before any team meeting, so they weren't defending a public position.

Result: The feature moved to the next planning cycle. We shipped a higher-priority item. The enterprise client was managed through a roadmap communication from the stakeholder — which actually strengthened the relationship because we gave them a timeline, not a 'no.'

My principle: disagree with evidence, not opinion. Do it privately and constructively before it becomes a room-level debate. And always give the senior stakeholder a way to change direction without losing face.`,
    tip: "The 'without losing face' framing shows political maturity. Dr. Vouk has navigated 20+ years of enterprise stakeholder dynamics. This will resonate.",
  },
  {
    id: 8,
    category: "Behavioral",
    difficulty: "Medium",
    mustKnow: false,
    question: "Tell me about a time you received critical feedback. How did you handle it?",
    answer: `Show growth orientation and ego management.

"Early in my role at Aasaan App, I presented a funnel analysis to the growth team lead. My analysis was technically correct, but I presented it in a way that implied the team had been making poor decisions — I led with what was broken rather than what the data suggested we should do next. The feedback I received was direct: 'Your analysis is good. Your delivery makes people defensive. That's your job to fix, not theirs.'

That landed. I realized I was optimizing for being right rather than being useful. I went back and rebuilt the presentation — same data, different framing. Instead of 'here's what's wrong,' it became 'here's the opportunity we've been missing, and here's how we capture it.' The same stakeholders who were defensive became advocates for the new direction.

Since then, I lead with recommendation and opportunity before evidence and diagnosis. The data is still there — it's just in service of a decision, not a verdict.

I'd expect to receive the same quality of feedback in this role, and I'd want it. I'd rather be corrected early than be wrong at scale."`,
    tip: "Dr. Vouk is a direct, high-feedback leader based on her public presence. She wants someone who takes feedback and improves, not someone who crumbles or deflects.",
  },
  {
    id: 9,
    category: "Product Thinking",
    difficulty: "High",
    mustKnow: true,
    question: "If you had 3 engineering sprints to improve ClearScape Analytics' ModelOps — how would you prioritize?",
    answer: `Lead with framework, then get specific.

"I'd anchor to three inputs: user pain intensity by persona, strategic fit with the current ModelOps roadmap, and implementation complexity — essentially a weighted RICE model applied to sprint-level decisions.

First, I'd segment by persona. ClearScape serves at least three distinct users: data scientists who need fast, reliable model deployment; business analysts who need AutoML with guardrails; and IT/admin teams who need governance, auditability, and cost control. Each persona has different pain at different workflow stages.

Given what I know about the recent ModelOps enhancements — unified platform, ONNX support, LLMOps for Azure OpenAI and Bedrock — I'd guess the most under-served segment right now is the business analyst who wants to build and deploy a model without writing code or involving a data scientist.

My sprint allocation:
- Sprint 1: Reduce onboarding friction for non-technical users. Improve the AutoML interface to deliver first-model-deployed in under 30 minutes. This expands the addressable user base immediately.
- Sprint 2: Add governance visibility for IT administrators — model health dashboards, cost-per-project tracking, audit logs. This is the approval blocker in enterprise deals.
- Sprint 3: Deepen the LLMOps integrations — specifically, one-click deployment for NVIDIA NIM models in GPU environments and standardized LLM Model Cards for transparency.

I'd validate this sequencing with 3-5 customer discovery calls and one session with the sales team on their top three deal-blocking objections before locking sprint scope."`,
    tip: "Do not give a generic framework answer. Show you know ClearScape's actual product. Dr. Vouk will test your depth here.",
  },
  {
    id: 10,
    category: "Product Thinking",
    difficulty: "High",
    mustKnow: true,
    question: "How would you define and measure success for a new analytics feature post-launch?",
    answer: `Three-layer measurement framework — show it's a system, not a metric.

"I think about success measurement in three layers.

Layer 1 — Adoption health (leading indicators, weeks 1-4):
- Feature activation rate: % of eligible users who trigger the feature at least once
- Time-to-first-value: how quickly a new user reaches a meaningful outcome (e.g., first model deployed, first dashboard published)
- Feature frequency: are users returning to it, or is it a one-time curiosity click?

Layer 2 — Business impact (lagging indicators, months 1-3):
- Retention delta for users who adopt the feature vs. those who don't — this is the core proof point
- Upsell rate to higher tiers or add-on products driven by feature engagement
- Support ticket reduction for the problem the feature was supposed to solve

Layer 3 — Signal quality (qualitative, ongoing):
- NPS verbatims filtered for feature mentions
- Customer success call themes — what do customers say when they describe using or not using the feature?
- Win/loss data — is this feature showing up as a reason customers chose Teradata over a competitor?

For a ModelOps-specific feature, I'd add two domain-specific metrics: model deployment frequency per customer (are they actually operationalizing more models?) and model monitoring alert rate (are they catching drift earlier, which means better governance?). Those tell me whether we delivered on the actual promise.

The North Star metric for an analytics platform APM: 'models in production per customer, trending up.' Everything else is in service of that."`,
    tip: "The three-layer framework is memorable and rigorous. The domain-specific ModelOps metrics at the end prove you understand the product deeply.",
  },
  {
    id: 11,
    category: "Product Thinking",
    difficulty: "Medium",
    mustKnow: true,
    question: "A customer says 'your analytics platform is too complex.' How do you respond as a PM?",
    answer: `Show diagnostic rigor — complexity is a symptom, not a diagnosis.

"'Too complex' is a symptom. My first move is diagnosis, not solution.

I'd want to know three things: Too complex for whom? Doing what? At what moment in their workflow?

A data scientist hitting complexity when trying to import a Bring-Your-Own-Model is a different problem than a business analyst who can't find the AutoML starting point, which is different again from a CXO who can't interpret model output without a data team translating it.

Discovery process: I'd run structured interviews with churned users and low-engagement accounts specifically — not just power users who've self-selected into the platform. I'd pull support ticket data filtered for onboarding and complexity keywords. I'd watch session recordings at the friction points. And I'd run a time-to-value benchmark: how long does it take a new user to produce their first meaningful output?

Then I'd quantify: how many users hit this friction point, at which stage, and what does it cost us in activation rate or renewal risk? This becomes a business case, not just a UX complaint.

The fix might be: UI/UX simplification, an improved onboarding flow, a low-code abstraction layer like AutoML for analysts, or better documentation. At Teradata's scale, it's often all four, but for different personas.

The hardest product design tension here is one I'd name explicitly: how do you make a platform accessible to business analysts without removing the depth enterprise data scientists rely on? That's a segmentation problem that requires either progressive disclosure in the UI or persona-specific entry points — and it's worth a full discovery cycle to get right."`,
    tip: "Naming the segmentation tension shows you're thinking at a product strategy level, not just a feature level. This will impress Dr. Vouk.",
  },
  {
    id: 12,
    category: "Product Thinking",
    difficulty: "Medium",
    mustKnow: false,
    question: "How would you approach drafting a user story for a non-technical business analyst using ClearScape's AutoML?",
    answer: `Show your user story craft with a real example.

"I'd start with the persona and job-to-be-done before writing a single line of the story.

Persona: Priya, a business analyst at a retail bank. She has strong Excel and SQL skills, understands the business domain well, but has no data science background. She needs to predict customer churn for her portfolio — but every time she's tried to work with the data science team, she's waited 6 weeks for a model.

Job-to-be-done: 'Help me build and deploy a churn prediction model I can own and update myself, without writing code or waiting for data science.'

User Story:
As a business analyst with SQL knowledge but no ML background,
I want to train a churn prediction model on my customer dataset using a guided AutoML workflow,
So that I can identify at-risk customers before month-end and brief my manager with confident, model-backed recommendations.

Acceptance Criteria:
- User can upload or connect a dataset from VantageCloud without writing code
- AutoML interface surfaces 3 recommended model types with plain-English descriptions of trade-offs
- Training completes and a scored output is available within [X minutes] for a dataset of [Y rows]
- Model performance is explained in business terms (e.g., 'This model correctly identifies 8 out of 10 at-risk customers')
- User can schedule retraining without engineering support

That's the level of specificity I'd bring to every story — so that the developer has a contract, QA has clear pass/fail criteria, and the business stakeholder can validate the outcome without reading code."`,
    tip: "This is a core JD requirement. Show you can do it — don't just say you can. Dr. Vouk will value the specificity here.",
  },
  {
    id: 13,
    category: "Product Thinking",
    difficulty: "High",
    mustKnow: false,
    question: "How would you conduct competitive research on Databricks or Snowflake for Teradata's analytics strategy?",
    answer: `Jobs-to-be-done lens, not feature checklist.

"I'd start with the right question: what jobs are customers doing on Databricks or Snowflake that they can't do on Teradata — and why do they choose to go there?

My research sources, in order:

1. Win/loss analysis with Teradata's sales team. What are the top three reasons we lose deals? What features or capabilities come up most? This is the highest-signal input and usually the most underused.

2. G2, Gartner Peer Insights, Reddit data engineering communities. These have candid, unfiltered comparisons. Filter for enterprise accounts — SMB perceptions of these platforms are different from enterprise ones.

3. Competitor changelogs and release notes. This reveals prioritization, not just capability. If Databricks has shipped three consecutive releases improving governance tooling, that tells me where they think their competitive gap is.

4. Analyst reports — Gartner Magic Quadrant, Forrester Wave. Not for the rankings, but for the criteria they use to evaluate platforms. That's essentially the category's product specification.

5. Job postings at target customers. If 10 enterprise banks are all hiring 'Databricks Data Engineer,' that's a signal about where enterprise adoption is moving.

Synthesis format: I'd deliver a 2x2 — where Teradata is winning and why, where we're losing and why, what's table stakes to match, and what's a genuinely defensible moat to double down on.

My hypothesis for Teradata: the moat is trusted AI at petabyte scale with enterprise governance built in. Databricks and Snowflake are fast on features but they cannot replicate 45 years of enterprise data trust overnight. That's where I'd recommend concentrating differentiation messaging and product investment."`,
    tip: "The job posting insight is unexpected and shows sophisticated competitive intelligence thinking. Use it.",
  },
  {
    id: 14,
    category: "Technical & Domain",
    difficulty: "High",
    mustKnow: true,
    question: "What do you understand about ClearScape Analytics and what makes it differentiated from other analytics platforms?",
    answer: `Lead with the architecture, then the business value, then the evidence.

"ClearScape Analytics is Teradata's end-to-end AI/ML capability suite embedded in VantageCloud. The core architectural differentiator is in-database execution — models run where the data lives, minimizing data movement. In enterprise environments with petabyte-scale datasets, moving data is expensive in three ways: latency, cost, and compliance exposure. ClearScape eliminates that friction.

The full lifecycle it covers: data preparation and feature engineering, model training and selection, real-time or batch scoring, and end-to-end ModelOps including monitoring, retraining, drift detection, governance, and retirement. It also supports an open ecosystem — Bring Your Own Model, Bring Your Own Analytics — so data scientists aren't locked into a single toolchain.

The recent ModelOps enhancements make it more competitive for enterprise GenAI use cases: unified support for ONNX embedding models, native integration with Azure OpenAI, Amazon Bedrock, and Google Gemini without custom development, GPU-native deployment of NVIDIA NIM LLMs, and LLM Model Cards for governance and transparency.

The business case is documented: Forrester found 244% ROI over three years and $125 million in profits for a Teradata customer running ClearScape. That's the number that gets a CFO to sign an enterprise contract.

Where I think the differentiation is hardest to replicate: governance at scale. Any cloud vendor can offer a model training environment. Very few can offer the audit trail, data lineage, access controls, and compliance reporting that large banks, insurers, and government agencies need before they'll put a model into a production decision workflow. That's where Teradata's enterprise DNA is a structural advantage."`,
    tip: "Dr. Vouk owns this product. She will test whether you understand it at depth, not just from the homepage. The Forrester numbers and ModelOps details signal real preparation.",
  },
  {
    id: 15,
    category: "Technical & Domain",
    difficulty: "High",
    mustKnow: true,
    question: "What is ModelOps and why does it matter in enterprise AI deployments?",
    answer: `Define it precisely, then explain the enterprise problem it solves.

"ModelOps is the practice — and the tooling — for managing the full lifecycle of machine learning models in production: deployment, versioning, monitoring, retraining, drift detection, governance, and retirement. It's to ML what DevOps is to software — the discipline that makes the output of data science teams reliable and scalable in real-world environments.

Why it matters in enterprise: the gap between 'model that works in a notebook' and 'model that runs in production reliably at scale' is enormous, and most organizations fall into it. Data drifts. Business conditions change. Regulatory requirements evolve. Without ModelOps, enterprises accumulate technical debt in the form of stale models making stale decisions — often without knowing it.

ClearScape's ModelOps addresses this with: a unified management interface across all model types (classical ML, AutoML, LLMs), automated monitoring with configurable drift alerts, full lifecycle management for LLMs including usage analytics and cost-per-project tracking, and low-code AutoML for non-technical users.

From a product perspective, the most important insight about ModelOps is that adoption is a product design problem, not just a technical one. Data scientists will use whatever tool deploys their model fastest. Business analysts need it to be as simple as a SaaS dashboard. IT teams need the governance layer to be comprehensive enough to satisfy their security review. A single ModelOps product has to serve all three without compromising for any of them — that's a hard design challenge and a real competitive moat for anyone who gets it right."`,
    tip: "The 'adoption is a product design problem' framing at the end shows you think as a PM, not just a technical analyst. This matters to Dr. Vouk.",
  },
  {
    id: 16,
    category: "Technical & Domain",
    difficulty: "Medium",
    mustKnow: false,
    question: "How does Teradata's in-database analytics approach differ from a traditional ETL-to-data-lake approach?",
    answer: `Make the architectural difference concrete with a business analogy.

"The traditional approach: extract data from your source systems, transform it, load it into a data lake or warehouse, and then run analytics on the copy. Every step introduces latency, cost, and a new attack surface for compliance teams. For a bank with petabytes of transaction data, this means a model that was trained on yesterday's data making decisions today — and a data movement trail that their compliance team has to audit.

Teradata's in-database approach: analytics and ML execute where the data lives, inside the Vantage engine. No extract, no copy, no movement. The model runs on the actual production dataset with full access controls and lineage intact.

The practical differences for an enterprise:
- Latency: real-time scoring at the point of decision, not batch inference on stale exports
- Cost: data egress fees from cloud environments are real and significant at scale — elimination is material
- Compliance: GDPR, CCPA, HIPAA, and financial services regulations all create requirements around data residency and movement. In-database eliminates entire categories of compliance risk
- Performance: Teradata's massively parallel processing (MPP) architecture means analytical queries on petabyte-scale datasets that would take hours on a general-purpose cloud compute cluster can be executed in seconds

The analogy I'd use with a business stakeholder: it's the difference between making dinner at home versus shipping all your ingredients to a restaurant kitchen, having them cook it, and shipping the meal back. In-database is cooking at home — faster, cheaper, and you never lose custody of the ingredients."`,
    tip: "The dinner analogy makes this memorable. Dr. Vouk regularly presents to C-suite audiences — she'll appreciate that you can explain technical concepts in accessible terms.",
  },
  {
    id: 17,
    category: "Technical & Domain",
    difficulty: "Medium",
    mustKnow: false,
    question: "You have SQL and Python experience. How would you apply that in this APM role?",
    answer: `Be specific — don't just say 'I'd use it for data analysis.'

"SQL and Python aren't credentials in this role — they're tools for PM judgment. Let me be specific about how I'd use each.

SQL: I'd use it to pull my own product usage data rather than waiting for a data team report. If I want to know which feature was last touched by churned accounts in the 30 days before cancellation, I should be able to write that query myself. At Aasaan App, I ran cohort queries directly on our database to understand retention by acquisition channel — that speed of self-service analytics is what lets a PM move faster than a bi-weekly sprint report.

Python: At Aasaan, I used scikit-learn to build the lead-scoring model. In this role, I'd use Python primarily for two things: quick data exploration when a hypothesis needs testing and a full BI report would take three days, and automation of recurring research tasks — for example, scraping competitor changelog data weekly to track their release cadence.

More importantly: having this technical background makes me a better partner to data scientists and engineers. I can read a model evaluation report and ask a real question about precision-recall tradeoffs. I can look at a feature specification and flag where a data dependency will create a pipeline bottleneck. I'm not a data scientist, but I speak enough of the language to not be a translation bottleneck between business and engineering.

In an analytics product team specifically, that dual fluency — business outcomes and technical architecture — is probably the most valuable thing an early-career PM can bring."`,
    tip: "Don't undersell this. Dr. Vouk has a PhD and expects technical fluency. But position it correctly: tools in service of better PM judgment, not credentials.",
  },
  {
    id: 18,
    category: "Stakeholder & Strategy",
    difficulty: "High",
    mustKnow: true,
    question: "What is Teradata's strategy around agentic AI and how does it connect to the analytics platform?",
    answer: `Show strategic awareness, not just product knowledge.

"Teradata is positioning itself as the context foundation and governance backbone for enterprise AI agents — not just as an analytics platform. The strategic thesis is: as AI agents multiply across enterprise workflows, they need grounded, trusted data to act on. Without that grounding, agents hallucinate on general training data and make decisions that can't be audited or explained to regulators.

Teradata provides three things that agents need: deep business context from decades of enterprise data, a governance layer that makes agent decisions auditable and compliant, and the performance backbone to run agent workloads at production scale across cloud, on-premises, and hybrid environments.

The product evidence: AI Factory and AgentBuilder enable enterprises to deploy agents that are connected to actual business data. The Analyst Agent on Microsoft Marketplace brings conversational analytics into Azure environments with transparency built in — powered by Teradata Agent Telemetry, which is the governance layer.

The strategic bet Teradata is making: enterprise AI adoption will stall on trust and governance, not capability. Every large enterprise has now run an AI pilot. Most are stuck at scaling it because they can't explain the decision, can't audit the model, or can't satisfy their compliance team. Teradata's 45-year enterprise pedigree is the structural advantage in exactly that environment.

As an APM supporting the analytics team, understanding this strategy matters because it shapes how I'd think about every feature prioritization decision. The question isn't just 'does this capability work?' — it's 'does this capability make enterprise AI more trustworthy and auditable?' That's the frame I'd apply."`,
    tip: "This shows you've read beyond the product pages. Dr. Vouk literally works on this agentic AI strategy. Demonstrating awareness of it signals you'd be a strategic asset, not just an executor.",
  },
  {
    id: 19,
    category: "Stakeholder & Strategy",
    difficulty: "Medium",
    mustKnow: false,
    question: "How would you support a senior PM in building a product roadmap? Walk me through your process.",
    answer: `Show you're a multiplier, not a burden.

"My goal in supporting a senior PM is to increase their bandwidth and decision quality, not add coordination overhead. Here's how I'd approach a roadmap cycle:

Step 1 — Intake and signal gathering. I'd own the research inputs: customer feedback synthesis from support tickets and CS calls, competitive intelligence summary, usage data pull for underperforming and over-performing features, and stakeholder interview notes from sales and presales. I'd deliver these in a standard format the senior PM can work from directly.

Step 2 — First-cut prioritization. I'd run a RICE or weighted scoring framework on the candidate features and produce a ranked backlog with justification for each item. The senior PM doesn't have to start from a blank page — they review and adjust my first cut.

Step 3 — Documentation. I'd own PRD drafting, user story writing, and acceptance criteria. Every item that goes into sprint planning would have documentation complete before the planning session — so engineering time is spent deciding, not clarifying.

Step 4 — Roadmap communication. I'd draft the internal roadmap deck and the customer-facing roadmap narrative. The senior PM reviews and approves — they don't write it from scratch.

Step 5 — Tracking. I'd run the post-launch metrics tracking, flag anomalies, and bring a monthly performance summary to the senior PM with a recommendation for what to double down on or cut.

What I'm describing is taking the execution burden off a senior PM so their cognitive energy goes to strategy, customer relationships, and decisions that require their level of judgment — not to writing user stories."`,
    tip: "This is what the JD literally describes. Dr. Vouk wants someone who makes her senior PMs faster. Show you understand the leverage model.",
  },
  {
    id: 20,
    category: "Stakeholder & Strategy",
    difficulty: "Medium",
    mustKnow: false,
    question: "How do you think about the difference between what customers ask for versus what they actually need?",
    answer: `Classic PM insight question — answer with lived evidence.

"Customers describe symptoms, not root causes. And they describe solutions, not problems. The job of a PM is to translate both into the underlying need.

My clearest example: at Aasaan App, merchants frequently requested 'a better dashboard.' That's a solution request. When I ran discovery calls and asked 'walk me through the last time you needed data to make a decision — what did you do?' — the actual answer was: they opened three different browser tabs, manually compared numbers in Excel, and still weren't confident in the output. The need wasn't a better dashboard. The need was a single, trusted view of their business performance that they could act on without cross-referencing spreadsheets.

That's a completely different product problem. A better dashboard might be the answer — or it might be better data integration, or a single alerting system, or a weekly automated summary. You can't know until you understand the job they're trying to do.

In an enterprise analytics context, this pattern is amplified. A CXO asking for 'more AI features' might actually need better model explainability so they can confidently present AI-driven decisions to their board. A data scientist asking for 'more model types' might actually need faster deployment for the models they already have. Getting to the underlying need is the work.

My practice: whenever a stakeholder brings me a solution request, I ask 'tell me about the last time this problem cost you something — what happened?' That question always surfaces the actual need underneath the stated want."`,
    tip: "The Aasaan story is concrete and specific. The enterprise framing shows you're already thinking in Teradata's context.",
  },
  {
    id: 21,
    category: "Stakeholder & Strategy",
    difficulty: "High",
    mustKnow: false,
    question: "What do you think is the biggest challenge facing enterprise analytics teams right now, and how does Teradata address it?",
    answer: `Show strategic opinion — not a neutral encyclopedia answer.

"The biggest challenge is the gap between AI proof-of-concept and AI in production. Almost every large enterprise has completed at least one AI pilot. Most are stuck at scaling it.

The reasons are consistent and well-documented: data governance issues that make compliance teams uncomfortable, model drift that no one is monitoring, business stakeholders who don't trust outputs they can't explain, and integration complexity with 20-year-old legacy systems that weren't designed for ML pipelines.

The failure mode I see most often: a data science team builds a model that performs beautifully in testing, hands it to IT for deployment, and six months later the model is still in a staging environment because no one owns the operationalization path.

Teradata addresses this at three layers:
- The infrastructure layer: VantageCloud handles scale, performance, and hybrid cloud deployment without requiring enterprises to rebuild their data architecture
- The operationalization layer: ClearScape Analytics and ModelOps provide the deployment, monitoring, drift detection, and governance tooling that turns a notebook model into a production-grade decision system
- The trust layer: the governance capabilities — audit trails, model cards, lineage tracking, role-based access — give compliance and legal teams the documentation they need to approve AI in regulated workflows

What Teradata can't do by itself: change the organizational dynamics that prevent AI adoption. That's a product marketing and customer success problem, not just a product problem. But the platform is correctly positioned for this moment.

If I were prioritizing product investment right now, I'd focus on making the distance between 'model trained' and 'model in production' as short as possible — with every step auditable. That's the unlock."`,
    tip: "Having a concrete opinion shows strategic confidence. Dr. Vouk will test whether you're a thinker or just a summarizer. Be a thinker.",
  },
  {
    id: 22,
    category: "Stakeholder & Strategy",
    difficulty: "Medium",
    mustKnow: false,
    question: "How would you prepare a competitive analysis for a product strategy discussion with senior leadership?",
    answer: `Show you can make research executive-ready.

"A competitive analysis for senior leadership has to answer three questions: where are we winning and why, where are we losing and why, and what should we do about it? Everything else is supporting evidence.

My process:

Week 1 — Signal gathering. Win/loss data from sales (highest signal, most underused). G2 and Gartner Peer Insights reviews filtered for enterprise accounts. Competitor changelogs for the last 6 months — this reveals their prioritization, not just their capabilities. Analyst reports for category criteria. Job postings at target customers to understand where adoption is moving.

Week 2 — Synthesis. I'd build a 2x2 — Teradata's relative strength versus competitive importance — to separate 'areas where we're behind on things customers care about' from 'areas where we're behind on things that don't actually win deals.' Those require different responses.

Week 3 — Recommendation. The output I'd bring to leadership isn't a feature comparison table. It's: here are the two or three places where competitive investment would have disproportionate deal impact, here's the evidence, here's the recommended response (build, partner, or position differently), and here's how we'd measure whether the response worked.

For Teradata specifically: I'd lead with the governance and trust differentiation story. Databricks and Snowflake are closing the capability gap quickly. The enduring moat is enterprise trust at scale — and the competitive analysis should help leadership decide where to invest to widen it, not just defend it."`,
    tip: "The 'build, partner, or position differently' trichotomy is a sophisticated strategic framing. It shows you understand that competitive response isn't always about building features.",
  },
  {
    id: 23,
    category: "Technical & Domain",
    difficulty: "Medium",
    mustKnow: false,
    question: "How would you think about demo creation for a ClearScape Analytics capability?",
    answer: `Show you understand demos as product communication, not just feature showcases.

"A great product demo is a story with a business problem at the center — not a feature tour. The mistake most demos make is leading with the technology. The right structure leads with the pain.

For a ClearScape Analytics ModelOps demo, I'd structure it in four acts:

Act 1 — The problem. 'Your data science team built a churn model six months ago. It worked great in testing. Today, it's running in production but no one knows if it's still accurate, who approved it, or what happens when it drifts. Here's what that looks like without ModelOps.' Show the friction, the manual processes, the uncertainty.

Act 2 — The transition. 'Now here's the same scenario with ClearScape's ModelOps.' Walk through the workflow — model registration, deployment, monitoring dashboard, drift alert, one-click retraining, governance log.

Act 3 — The outcome. 'This model has been in production for 6 months. Here's the performance trend. Here's the audit trail your compliance team can export. Here's the cost-per-project breakdown for your CFO.' Make the value concrete and multi-stakeholder.

Act 4 — The invitation. 'Here's your free hands-on environment. Try it with your own dataset.' Always end with a path to self-service.

My role in supporting senior PMs on demo creation would be to own the first draft of the narrative, source the right dataset for the demo scenario, and validate the technical accuracy with the engineering team before the PM reviews and refines."`,
    tip: "The JD explicitly mentions demo support as a core responsibility. Showing you've thought through the structure will differentiate you.",
  },
  {
    id: 24,
    category: "Closing",
    difficulty: "Medium",
    mustKnow: true,
    question: "Where do you see yourself in this APM role in 12-18 months?",
    answer: `Ambition balanced with realism — show you're here to grow, not just pass through.

"In 12-18 months, I want to be the person a senior PM reaches for when they need something done without hand-holding. Not just executing tasks, but anticipating what's needed next.

Concretely: I'd expect to own end-to-end the discovery and documentation cycle for at least one significant feature — from customer interviews to user stories to post-launch metrics reporting. I'd want to have built a working understanding of ClearScape's customer base deep enough that I could run a discovery call independently and bring back synthesis that's immediately useful.

I'd also want to have built relationships across the cross-functional teams — engineering, data science, sales, customer success — so I'm a connector, not a gatekeeper.

The growth I'm aiming for: moving from 'someone who executes with oversight' to 'someone who can own a problem end-to-end and surface the senior PM-level decision, not the research.' That transition — from research executor to strategic contributor — is what I'd use as my internal benchmark for whether I'm on track.

And at 18 months, I'd want Dr. Vouk to be thinking about expanding my scope — not because I pushed for it, but because the quality of my work made the expansion obvious."

Why it works: Specific, measurable, humble about the ramp but ambitious about the destination. And ending with Dr. Vouk as the judge is a subtle but powerful signal of trust in her leadership.`,
    tip: "End by naming Dr. Vouk as the person whose judgment you trust to evaluate your growth. It's a genuine compliment and a smart close.",
  },
  {
    id: 25,
    category: "Closing",
    difficulty: "High",
    mustKnow: true,
    question: "Do you have any questions for me? (Your Questions for Dr. Vouk)",
    answer: `Your questions are as important as your answers. Ask questions that signal strategic depth.

QUESTION 1 — On her domain expertise:
"You've driven AI adoption at both IBM and Teradata across very different enterprise contexts. What's the most common mistake enterprises make when they try to operationalize AI — and how has ClearScape Analytics been specifically designed to prevent it?"

Why it works: Positions her as the expert, signals you understand the operationalization problem, and will get you intelligence you can't get from public sources.

---

QUESTION 2 — On product priorities:
"The recent ModelOps enhancements expanded support for ONNX, LLMOps, and agentic AI workflows. As you think about the next 12-18 months, what's the product surface area where you're most focused — and where does the APM role play the most critical supporting function?"

Why it works: Shows you've done product research at depth, and signals you're thinking about how to contribute, not just how to get the job.

---

QUESTION 3 — On team culture:
"Given that you've built and scaled product teams at IBM and now at Teradata — what's the one behavior or habit you'd want an early-career PM on your team to develop in their first 90 days to be genuinely effective here?"

Why it works: Framing around her experience, asking for practical wisdom, and positioning yourself as someone who wants to learn from her specifically.

---

QUESTION 4 — On the APM path:
"How do you think about the progression from APM to PM in this team — what does someone have to demonstrate to earn that transition?"

Why it works: Signals ambition, accountability, and respect for the process. Dr. Vouk will appreciate directness about career growth expectations.`,
    tip: "Ask at most 2-3 questions. Pick the ones that feel most natural in the flow of your conversation. Question 1 and 3 are the strongest pair.",
  },
];

const difficultyColors = {
  High: "bg-red-100 text-red-700 border border-red-200",
  Medium: "bg-yellow-100 text-yellow-700 border border-yellow-200",
  Low: "bg-green-100 text-green-700 border border-green-200",
};

export default function InterviewPrep() {
  const [activeCategory, setActiveCategory] = useState("All");
  const [openQuestion, setOpenQuestion] = useState(null);
  const [showMustKnow, setShowMustKnow] = useState(false);
  const [progress, setProgress] = useState({});

  const cats = ["All", ...Object.keys(categories)];
  const filtered = questions.filter(q => {
    const catMatch = activeCategory === "All" || q.category === activeCategory;
    const mkMatch = !showMustKnow || q.mustKnow;
    return catMatch && mkMatch;
  });

  const toggleDone = (id) => {
    setProgress(p => ({ ...p, [id]: !p[id] }));
  };

  const doneCount = Object.values(progress).filter(Boolean).length;
  const totalCount = questions.length;
  const pct = Math.round((doneCount / totalCount) * 100);

  return (
    <div style={{ fontFamily: "'Georgia', 'Times New Roman', serif", background: "#0f1117", minHeight: "100vh", color: "#e8e0d0" }}>
      {/* Header */}
      <div style={{
        background: "linear-gradient(135deg, #0f1117 0%, #1a1f2e 50%, #0f1117 100%)",
        borderBottom: "1px solid #2a2f3f",
        padding: "48px 32px 36px",
        position: "relative",
        overflow: "hidden"
      }}>
        <div style={{
          position: "absolute", top: 0, left: 0, right: 0, bottom: 0,
          backgroundImage: "radial-gradient(ellipse at 20% 50%, rgba(59,158,221,0.08) 0%, transparent 60%), radial-gradient(ellipse at 80% 20%, rgba(168,85,247,0.06) 0%, transparent 50%)",
          pointerEvents: "none"
        }} />
        <div style={{ maxWidth: 900, margin: "0 auto", position: "relative" }}>
          <div style={{ display: "flex", alignItems: "center", gap: 12, marginBottom: 8 }}>
            <div style={{ width: 6, height: 6, borderRadius: "50%", background: "#22c55e", boxShadow: "0 0 8px #22c55e" }} />
            <span style={{ fontSize: 11, letterSpacing: "0.2em", textTransform: "uppercase", color: "#6b7280", fontFamily: "monospace" }}>FINAL ROUND PREP · LIVE DOCUMENT</span>
          </div>
          <h1 style={{ fontSize: "clamp(28px, 5vw, 48px)", fontWeight: 700, letterSpacing: "-0.02em", margin: "0 0 8px", lineHeight: 1.1 }}>
            Teradata APM Interview
            <span style={{ display: "block", background: "linear-gradient(90deg, #3b9edd, #a855f7)", WebkitBackgroundClip: "text", WebkitTextFillColor: "transparent", backgroundClip: "text" }}>
              Master Guide
            </span>
          </h1>
          <p style={{ color: "#9ca3af", fontSize: 15, margin: "0 0 28px", maxWidth: 560, lineHeight: 1.6 }}>
            25 high-probability questions with interview-grade answers. Tailored to Dr. Meeta Y Vouk, VP Product — Analytics & AI/ML.
          </p>

          {/* Stats row */}
          <div style={{ display: "flex", gap: 24, flexWrap: "wrap" }}>
            {[
              { label: "Questions", value: "25" },
              { label: "Categories", value: "6" },
              { label: "Must-Know", value: questions.filter(q => q.mustKnow).length.toString() },
              { label: "Reviewed", value: `${doneCount}/${totalCount}` },
            ].map(s => (
              <div key={s.label} style={{ textAlign: "center" }}>
                <div style={{ fontSize: 28, fontWeight: 700, color: "#e8e0d0", lineHeight: 1 }}>{s.value}</div>
                <div style={{ fontSize: 11, color: "#6b7280", letterSpacing: "0.1em", textTransform: "uppercase", marginTop: 2 }}>{s.label}</div>
              </div>
            ))}
          </div>

          {/* Progress bar */}
          <div style={{ marginTop: 24 }}>
            <div style={{ display: "flex", justifyContent: "space-between", marginBottom: 6 }}>
              <span style={{ fontSize: 12, color: "#6b7280" }}>Practice Progress</span>
              <span style={{ fontSize: 12, color: "#22c55e" }}>{pct}%</span>
            </div>
            <div style={{ height: 4, background: "#1f2535", borderRadius: 2, overflow: "hidden" }}>
              <div style={{ height: "100%", width: `${pct}%`, background: "linear-gradient(90deg, #3b9edd, #22c55e)", transition: "width 0.5s ease", borderRadius: 2 }} />
            </div>
          </div>
        </div>
      </div>

      {/* Interviewer intel card */}
      <div style={{ maxWidth: 900, margin: "0 auto", padding: "24px 32px 0" }}>
        <div style={{
          background: "linear-gradient(135deg, #1a1f2e, #1e2538)",
          border: "1px solid #2a3a5c",
          borderRadius: 12,
          padding: "20px 24px",
          display: "flex",
          gap: 16,
          alignItems: "flex-start"
        }}>
          <div style={{ width: 44, height: 44, borderRadius: "50%", background: "linear-gradient(135deg, #3b9edd, #a855f7)", flexShrink: 0, display: "flex", alignItems: "center", justifyContent: "center", fontSize: 18, fontWeight: 700 }}>
            M
          </div>
          <div>
            <div style={{ display: "flex", alignItems: "center", gap: 8, marginBottom: 4 }}>
              <span style={{ fontWeight: 600, fontSize: 15 }}>Dr. Meeta Y Vouk</span>
              <span style={{ fontSize: 11, background: "#1a3a5c", color: "#3b9edd", padding: "2px 8px", borderRadius: 4, letterSpacing: "0.05em" }}>YOUR INTERVIEWER</span>
            </div>
            <div style={{ color: "#9ca3af", fontSize: 13, lineHeight: 1.6 }}>
              VP Product Management – Analytics & AI/ML · Teradata · PhD ASIC Design · NC State adjunct professor · Former IBM AI Director (20x adoption in 3 years) · Owns: Enterprise Vector Store, Feature Store, ModelOps, AI Workbench, Analytics Freedom
            </div>
            <div style={{ marginTop: 10, padding: "10px 14px", background: "rgba(59,158,221,0.08)", borderLeft: "3px solid #3b9edd", borderRadius: "0 6px 6px 0", fontSize: 13, color: "#c0d8f0", fontStyle: "italic" }}>
              ⚡ What she's screening for: Can you translate between technical depth and business value? Do you understand why enterprise AI is hard? Will you make her team faster?
            </div>
          </div>
        </div>
      </div>

      {/* Filters */}
      <div style={{ maxWidth: 900, margin: "0 auto", padding: "20px 32px 0" }}>
        <div style={{ display: "flex", gap: 8, flexWrap: "wrap", alignItems: "center" }}>
          {cats.map(cat => (
            <button
              key={cat}
              onClick={() => setActiveCategory(cat)}
              style={{
                padding: "6px 14px",
                borderRadius: 20,
                border: "1px solid",
                fontSize: 12,
                cursor: "pointer",
                transition: "all 0.2s",
                fontFamily: "inherit",
                letterSpacing: "0.02em",
                borderColor: activeCategory === cat ? "#3b9edd" : "#2a2f3f",
                background: activeCategory === cat ? "rgba(59,158,221,0.15)" : "transparent",
                color: activeCategory === cat ? "#3b9edd" : "#6b7280",
              }}
            >
              {cat}
            </button>
          ))}
          <button
            onClick={() => setShowMustKnow(m => !m)}
            style={{
              marginLeft: "auto",
              padding: "6px 14px",
              borderRadius: 20,
              border: "1px solid",
              fontSize: 12,
              cursor: "pointer",
              fontFamily: "inherit",
              transition: "all 0.2s",
              borderColor: showMustKnow ? "#f97316" : "#2a2f3f",
              background: showMustKnow ? "rgba(249,115,22,0.15)" : "transparent",
              color: showMustKnow ? "#f97316" : "#6b7280",
            }}
          >
            ★ Must-Know Only
          </button>
        </div>
        <div style={{ marginTop: 10, color: "#4b5563", fontSize: 12 }}>
          Showing {filtered.length} of {questions.length} questions
        </div>
      </div>

      {/* Questions */}
      <div style={{ maxWidth: 900, margin: "0 auto", padding: "16px 32px 60px" }}>
        {filtered.map((q, idx) => {
          const isOpen = openQuestion === q.id;
          const isDone = progress[q.id];
          const col = categoryColors[q.category];

          return (
            <div
              key={q.id}
              style={{
                marginBottom: 12,
                border: "1px solid",
                borderColor: isOpen ? col.accent + "60" : "#1f2535",
                borderRadius: 10,
                overflow: "hidden",
                transition: "all 0.25s ease",
                background: isOpen ? "rgba(255,255,255,0.02)" : "transparent",
              }}
            >
              {/* Question header */}
              <div
                onClick={() => setOpenQuestion(isOpen ? null : q.id)}
                style={{
                  padding: "16px 20px",
                  cursor: "pointer",
                  display: "flex",
                  alignItems: "flex-start",
                  gap: 14,
                  transition: "background 0.2s",
                }}
              >
                {/* Number */}
                <div style={{
                  width: 28, height: 28, borderRadius: 6,
                  background: isOpen ? col.accent : "#1f2535",
                  color: isOpen ? "#fff" : "#4b5563",
                  display: "flex", alignItems: "center", justifyContent: "center",
                  fontSize: 12, fontWeight: 700, flexShrink: 0,
                  transition: "all 0.2s", fontFamily: "monospace"
                }}>
                  {String(q.id).padStart(2, "0")}
                </div>

                <div style={{ flex: 1, minWidth: 0 }}>
                  {/* Tags row */}
                  <div style={{ display: "flex", gap: 6, marginBottom: 8, flexWrap: "wrap" }}>
                    <span style={{ fontSize: 10, padding: "2px 8px", borderRadius: 4, background: col.accent + "20", color: col.accent, fontFamily: "monospace", letterSpacing: "0.05em" }}>
                      {q.category}
                    </span>
                    <span className={difficultyColors[q.difficulty]} style={{ fontSize: 10, padding: "2px 8px", borderRadius: 4, fontFamily: "monospace" }}>
                      {q.difficulty}
                    </span>
                    {q.mustKnow && (
                      <span style={{ fontSize: 10, padding: "2px 8px", borderRadius: 4, background: "rgba(249,115,22,0.15)", color: "#f97316", fontFamily: "monospace" }}>
                        ★ MUST KNOW
                      </span>
                    )}
                    {isDone && (
                      <span style={{ fontSize: 10, padding: "2px 8px", borderRadius: 4, background: "rgba(34,197,94,0.15)", color: "#22c55e", fontFamily: "monospace" }}>
                        ✓ REVIEWED
                      </span>
                    )}
                  </div>
                  <div style={{ fontSize: 15, fontWeight: 600, color: "#e8e0d0", lineHeight: 1.4, paddingRight: 8 }}>
                    {q.question}
                  </div>
                </div>

                <div style={{ color: "#4b5563", fontSize: 18, flexShrink: 0, transition: "transform 0.2s", transform: isOpen ? "rotate(180deg)" : "rotate(0deg)" }}>
                  ↓
                </div>
              </div>

              {/* Answer */}
              {isOpen && (
                <div style={{ borderTop: "1px solid #1f2535" }}>
                  <div style={{ padding: "24px 20px 20px" }}>
                    {/* Answer text */}
                    <div style={{
                      fontSize: 14, lineHeight: 1.85, color: "#c9c0b0",
                      whiteSpace: "pre-wrap",
                    }}>
                      {q.answer}
                    </div>

                    {/* Interviewer tip */}
                    <div style={{
                      marginTop: 20,
                      padding: "12px 16px",
                      background: `linear-gradient(135deg, ${col.accent}15, ${col.accent}08)`,
                      border: `1px solid ${col.accent}30`,
                      borderRadius: 8,
                      fontSize: 13,
                      color: col.accent,
                      lineHeight: 1.6
                    }}>
                      <span style={{ fontWeight: 700, fontFamily: "monospace", fontSize: 11, letterSpacing: "0.08em" }}>
                        INTERVIEWER INSIGHT ·{" "}
                      </span>
                      {q.tip}
                    </div>

                    {/* Mark reviewed */}
                    <div style={{ marginTop: 16, display: "flex", justifyContent: "flex-end" }}>
                      <button
                        onClick={(e) => { e.stopPropagation(); toggleDone(q.id); }}
                        style={{
                          padding: "8px 18px",
                          borderRadius: 6,
                          border: "1px solid",
                          fontSize: 12,
                          cursor: "pointer",
                          fontFamily: "inherit",
                          letterSpacing: "0.05em",
                          transition: "all 0.2s",
                          borderColor: isDone ? "#22c55e" : "#2a2f3f",
                          background: isDone ? "rgba(34,197,94,0.15)" : "rgba(255,255,255,0.03)",
                          color: isDone ? "#22c55e" : "#6b7280",
                        }}
                      >
                        {isDone ? "✓ Marked as Reviewed" : "Mark as Reviewed"}
                      </button>
                    </div>
                  </div>
                </div>
              )}
            </div>
          );
        })}
      </div>

      {/* Footer */}
      <div style={{
        borderTop: "1px solid #1f2535",
        padding: "24px 32px",
        textAlign: "center",
        color: "#374151",
        fontSize: 12,
        fontFamily: "monospace",
        letterSpacing: "0.08em"
      }}>
        PREPARED FOR YASHWANTH REDDY YATHAM · TERADATA APM FINAL ROUND · {new Date().getFullYear()}
      </div>
    </div>
  );
}
