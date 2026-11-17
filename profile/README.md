# OCaml Bench

OCaml Bench brings together the community's work on measuring the performance of the OCaml compiler, runtime and ecosystem. We want results that compiler developers can act on before a PR is merged, that release teams can use to compare versions (OCaml 5.x, trunk, [OxCaml](https://github.com/oxcaml/oxcaml/)), and that anyone can reproduce on their own machine using the same tools that run in CI. 

Start with the [Sandmark wiki](https://github.com/ocaml-bench/sandmark/wiki), which has an overview of the project, how the pieces fit together, and the design of the upcoming benchmarking service. The [Sandmark 3.0 roadmap](https://github.com/ocaml-bench/sandmark/wiki/Sandmark-3.0) shows our current roadmap. 

Questions, new benchmarks and bug reports are welcome on any of the repositories below. We suggest consulting the README.md and contribution guide for each project.

## Projects

* [sandmark](https://github.com/ocaml-bench/sandmark): runs benchmarks on tuned machines providing visualisations of the results.
* [macro-benches](https://github.com/ocaml-bench/macro-benches): a suite of realistic OCaml applications in the style of [DaCapo](https://www.dacapobench.org/).
* [micro-benches](https://github.com/ocaml-bench/micro-benches): the classic suite of micro benchmarks, each exercising a particular part of the language or runtime, and runnable standalone with minimal setup.
