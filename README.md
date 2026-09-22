# Victor Martins

I build developer tools and small, reproducible experiments in systems performance.
My current focus is dependency review: making it easier to see what changed in the code we install.

### Working on

**[capsurface](https://github.com/VictorMartins3/capsurface)** — an offline tool for reviewing npm dependency updates.

It compares source scans against a reviewed baseline and points to newly observed filesystem, network, process-execution and credential-access indicators. The goal is to give reviewers a useful before/after, with source locations they can inspect locally or in a pull request.

It's early. I'm especially interested in real updates where the report is noisy, misses a change, or leaves you unsure what to review next.

[Try the demo](https://github.com/VictorMartins3/capsurface#terminal-demo) · [Report an issue](https://github.com/VictorMartins3/capsurface/issues)

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
