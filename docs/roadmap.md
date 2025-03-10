# Roadmap

In the spirit of transparency, we share our roadmap with the community — so while [DeepSource](https://deepsource.com) is steering this project, the community can see where we're headed and contribute to the direction of the project. This roadmap is a living document and will be updated as we make progress.


## What's supported today

Globstar is meant to be a light-weight, yet powerful, way of defining code quality and security checkers for your projects. Our [YAML interface](/reference/checker-yaml) allows single-file analysis and is easy to write and maintain — and should cover most of the use-cases you might have, in [20+ programming languages](/supported-languages) today. If you need sophisticated checkers, use the [Go interface](/reference/checker-go).

::: warning IMPORTANT
While the YAML interface is available in stable at the moment, the Go interface is still work-in-progress. We're actively working on it, and it should be available in the next couple of releases. This is a brand new project, with everything built from scratch, and we're working hard to sand off the rough edges. Please bear with us — and open [issues](https://github.com/DeepSourceCorp/globstar/issues) if you can. Better yet, send us [pull requests](/contributing)!
:::

## Future roadmap

- **More builtin checkers**: We've currently been focusing on the Globstar runtime itself, so there are only a few builtin checkers available today. This is one of our top priorities. We'll be adding more security checkers, especially for categories like OWASP Top 10 and SANS/CWE Top 25, and common code quality checkers. The goal is to make `globstar check` as useful as possible out of the box.

- **Imports and Scope Resolution**: This allows you to write sophisticated checkers that can understand the entire codebase, and not just a single file. We currently have support for this in the Go interface for Python and JavaScript, and will be adding support for other languages soon.

- **Concurrency**: Globstar runs sequentially today, with each checker running one after the other. While the runtime is fast enough, concurrency will make it even faster — especially for large codebases.

- **Support for more languages**: While we support most of the popular languages today, we'd like Globstar to be comprehensive.

- **Hosted Globstar**: We'll bring Globstar support natively to DeepSource, so you can run Globstar checks on your repositories without having to install anything. This will also give you access to everything DeepSource already offers — sophisticated quality and security gates, baseline analysis, ignored rules, centralized configuration, reports, and Autofix™ AI. 

## Get involved

We'd love you to help us shape the future of Globstar. If you have ideas, suggestions, or feedback, please [open a new thread](https://github.com/DeepSourceCorp/globstar/discussions) in our community or participate in an existing one. If you're a developer, you can also contribute to the project by [opening a pull request](https://github.com/DeepSourceCorp/globstar/pulls) or helping us with [issues](https://github.com/DeepSourceCorp/globstar/issues).