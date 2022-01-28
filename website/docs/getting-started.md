---
sidebar_position: 2
---

# Getting Started

Inlang takes 10 seconds to adopt and 1 second to get rid of. No lock-in whatsoever.

1. Create a project in [the dashboard](https://app.inlang.dev).
2. Import your translations either via copy & paste or [the CLI](/docs/cli).
3. Done :)

### Use inlang with existing translations

:::info
In case your software project does not use [Fluent](https://projectfluent.org) as i18n
syntax, check whether an [adapter](/docs/adapters) exists.
:::

### You want to start localizing (translate) your software

Some languages like Swift have an in-build localiation solution. For most other languages like JavaScript
you need a i18n (internationalization) library. The choice of the i18n library is up to you. If you
are in doubt, [ask in the forum](https://github.com/inlang/inlang/discussions) which i18n library
suits your project.

:::caution
Since inlang is build around [Fluent](https://projectfluent.org), whatever i18n library you end up choosing it
should use Fluent as syntax. Other syntaxes work as well but require an [adapter](/docs/adapters).
:::