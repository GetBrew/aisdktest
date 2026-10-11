# AI SDK fork

This repository is a fork of `vercel/ai`, not the Brew public API SDK.
The checked-out upstream snapshot is dated 2025-10-27. Preserve upstream
package, provider, example and release contracts; do not upgrade this tree to
match Brew's application dependency merely to align documentation.

The root [README](README.md) points to the AI package README. Package and
provider instructions live beside their source. Read the owning package's
manifest and tests before editing it. Keep Apache license notices and upstream
changelogs intact. Generated files must be changed through their generator.

Brew's maintained client contracts live in
[typescript-sdk](https://github.com/GetBrew/typescript-sdk),
[brew-cli](https://github.com/GetBrew/brew-cli), and
[public documentation](https://github.com/GetBrew/docs). This fork's examples
are AI SDK examples, not current Brew API integration instructions.

Run package-specific checks for functional changes. Upstream CI owns the full
monorepo build and test matrix. Never call external model APIs during an
offline documentation audit; the examples can require billable credentials.
