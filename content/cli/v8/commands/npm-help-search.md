---
title: npm-help-search
section: 1
description: Search npm help documentation
github_repo: npm/cli
github_branch: v8
github_path: docs/content/commands/npm-help-search.md
redirect_from:
  - /cli-commands/help-search
  - /cli-commands/help-search.html
  - /cli-commands/npm-help-search
  - /cli/commands/help-search
  - /cli/help-search
  - /cli/help-search.html
---

### Synopsis

<!-- AUTOGENERATED USAGE DESCRIPTIONS START -->
<!-- automatically generated, do not edit manually -->
<!-- see lib/commands/help-search.js -->

```bash
npm help-search <text>
```

<!-- automatically generated, do not edit manually -->
<!-- see lib/commands/help-search.js -->

<!-- AUTOGENERATED USAGE DESCRIPTIONS END -->

Note: This command is unaware of workspaces.

### Description

This command will search the npm markdown documentation files for the terms
provided, and then list the results, sorted by relevance.

If only one result is found, then it will show that help topic.

If the argument to `npm help` is not a known help topic, then it will call
`help-search`.  It is rarely if ever necessary to call this command
directly.

### Configuration

<!-- AUTOGENERATED CONFIG DESCRIPTIONS START -->
<!-- automatically generated, do not edit manually -->
<!-- see lib/utils/config/definitions.js -->
#### `long`

* Default: false
* Type: Boolean

Show extended information in `ls`, `search`, and `help-search`.

<!-- automatically generated, do not edit manually -->
<!-- see lib/utils/config/definitions.js -->

<!-- AUTOGENERATED CONFIG DESCRIPTIONS END -->

### See Also

* [npm](/cli/v8/commands/npm)
* [npm help](/cli/v8/commands/npm-help)
