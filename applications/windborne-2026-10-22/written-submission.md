# Prabhjeet Singh
## Software Engineer, Machine Learning Systems — WindBorne Systems

### Tell us about a problem you couldn’t leave alone. What did you build to fix it?

At DP World, incoming clients expected transaction volumes that our synchronous proforma-invoice flow could not support. I designed and implemented a Kafka-based asynchronous pipeline to replace that flow. I worked from client requirements and product input, then built the processing path around asynchronous work.

I also implemented configurable post-invoice workflows and a scheduler, and handled their production rollout across 22 clients and 12 downstream integrations. Different workflows needed different prerequisites and retry behavior. I made those configurable and added email notifications to developers and support when retries were exhausted. I wanted the implementation to cover what happens after an invoice is created, including the cases that need someone’s attention.

### Tell us about a time you had to understand an unfamiliar system that wasn’t behaving as expected. How did you get to the bottom of it?

At DP World, I worked on an existing proforma-to-invoice conversion flow whose latency needed improvement. Understanding the billing and entity-creation behavior was necessary before changing it. The issue involved redundant billing and entity duplication. I removed that redundant work, and conversion p95 fell from approximately seven seconds to 800 milliseconds.

The useful part of that investigation was understanding what the existing flow was doing before deciding what to change. The improvement came from removing unnecessary processing in the application.

### Describe a real coding task where AI tools helped you move faster. Where did you have to step in and think for yourself?

I used AI tools while building FinSight, my Python/FastAPI and React/TypeScript workbench for researching public company filings. AI assistance helped me move from the application design to working code more quickly. I remained responsible for deciding what counted as a supported answer and how a user could verify it.

In FinSight, financial calculations use deterministic code and filing facts rather than model-generated arithmetic. Retrieved passages have inspectable citations, and local-model synthesis is optional. Those boundaries matter because a fluent answer alone does not establish that the numbers, reporting periods, or source evidence are correct.

I also kept the evaluation claims limited. The recorded retrieval evaluation uses a small curated corpus and does not establish that hybrid retrieval is universally better. FinSight is a local prototype, not a production financial service.

### Describe the extent to which you have experience with production systems.

I spent July 2022 through August 2025 as a Software Development Engineer 1 at DP World, building and maintaining backend services for invoicing and cargo-offer applications. My work included the Kafka-based proforma-invoice pipeline, configurable post-invoice workflows, and production rollout across 22 clients and 12 downstream integrations.

I integrated seven external shipping-line APIs alongside an in-house source, using server-sent events to show offers as each source responded. I also implemented credit-note functionality and introduced team unit tests with an 80% coverage check in Azure DevOps.

That is my professional production experience. My current NYU deep-learning research is experimental, and projects such as FinSight are prototypes. I keep those separate from systems I have delivered in production.

### How many years of relevant experience do you have?

Three years of full-time professional software engineering experience at DP World, from July 2022 through August 2025. I also completed a software engineering internship at Deutsche Telekom Digital Labs in 2021 and am currently a graduate student researcher at NYU.

I completed my BE in Information Technology at Netaji Subhas Institute of Technology in 2022. My NYU MS in Computer Science is expected in May 2027, and I am available for full-time work from May 17, 2027. I have US work authorization and will need future sponsorship.
