# Victor Martins

**Software engineer · Distributed systems · Security · Performance**

[LinkedIn](https://www.linkedin.com/in/victormartins2/) · [X / Twitter](https://x.com/0xvmartins) · [Email](mailto:martins.victor212004@gmail.com)

I'm a software engineer based in São Paulo, Brazil. My background is in distributed backend systems, payment infrastructure and security engineering, working primarily with Rust and TypeScript.

I've worked on payment services, identity verification, authentication and event-driven processing, from implementation through deployment and production debugging. I also have a background in robotics and mechatronics.

In open source, I build developer tools and small, reproducible performance experiments in Rust, C, Go, JavaScript and Python. I like questions that can be investigated in code: what changed in a dependency, where a service spends its time, or why a loop is waiting for memory.

### Engineering background

- **Backend & infrastructure:** distributed services, APIs and asynchronous workflows; PostgreSQL, Redis, AWS, GCP, Kubernetes and Terraform.
- **Security:** authentication, cryptographic workflows and identity verification, with experience in payment and fraud-prevention systems.
- **Performance & reliability:** profiling, concurrency, observability and debugging across application, network and operating-system layers.

### Working on

**[capsurface](https://github.com/VictorMartins3/capsurface)** — an offline tool for reviewing npm dependency updates.

It compares source scans against a reviewed baseline and points to newly observed filesystem, network, process-execution and credential-access indicators. The goal is to give reviewers a useful before/after, with source locations they can inspect locally or in a pull request.

It's early. I'm especially interested in real updates where the report is noisy, misses a change, or leaves you unsure what to review next.

[Try the demo](https://github.com/VictorMartins3/capsurface#terminal-demo) · [Report an issue](https://github.com/VictorMartins3/capsurface/issues)

### Backend & systems

- **[credit-service](https://github.com/VictorMartins3/credit-service)** — a Go service for credit decisions, with configurable rules, concurrent processing, PostgreSQL, Redis and Prometheus metrics.
- **[payment-engine](https://github.com/VictorMartins3/payment-engine)** — a Rust transaction processor covering deposits, withdrawals, disputes and chargebacks, with decimal arithmetic and streaming CSV input.
- **[healthcare-api](https://github.com/VictorMartins3/healthcare-api)** — a Python/FastAPI project for patient records, clinical notes and AI-assisted summaries, backed by PostgreSQL.

### Performance experiments

I also write benchmarks to understand where time goes, from memory access to compiler behavior.

| Project | What it explores |
| --- | --- |
| [roofline-bench](https://github.com/VictorMartins3/roofline-bench) | Memory bandwidth and arithmetic intensity in CPU workloads modeled on LLM inference. C. |
| [cache-bench](https://github.com/VictorMartins3/cache-bench) | How matrix traversal order and data layout affect CPU cache behavior. C. |
| [mc-greeks-bench](https://github.com/VictorMartins3/mc-greeks-bench) | Finite differences, hand-written differentiation and compiler-generated derivatives for Monte Carlo option Greeks. Rust. |
| [trait-tax](https://github.com/VictorMartins3/trait-tax) | Dynamic dispatch versus a static processing pipeline. Rust. |

### Get in touch

For bugs, examples or technical questions, open an issue in the relevant repository.
You can also reach me at [martins.victor212004@gmail.com](mailto:martins.victor212004@gmail.com).
