---
title: npm-whoami
section: 1
description: Display npm username
github_repo: npm/cli
github_branch: v8
github_path: docs/content/commands/npm-whoami.md
redirect_from:
  - /cli-commands/npm-whoami
  - /cli-commands/whoami
  - /cli-commands/whoami.html
  - /cli/commands/whoami
  - /cli/whoami
  - /cli/whoami.html
---

### Synopsis

<!-- AUTOGENERATED USAGE DESCRIPTIONS START -->
<!-- automatically generated, do not edit manually -->
<!-- see lib/commands/whoami.js -->

```bash
npm whoami
```

<!-- automatically generated, do not edit manually -->
<!-- see lib/commands/whoami.js -->

<!-- AUTOGENERATED USAGE DESCRIPTIONS END -->

Note: This command is unaware of workspaces.

### Description

Display the npm username of the currently logged-in user.

If logged into a registry that provides token-based authentication, then
connect to the `/-/whoami` registry endpoint to find the username
associated with the token, and print to standard output.

If logged into a registry that uses Basic Auth, then simply print the
`username` portion of the authentication string.

### Configuration

<!-- AUTOGENERATED CONFIG DESCRIPTIONS START -->
<!-- automatically generated, do not edit manually -->
<!-- see lib/utils/config/definitions.js -->
#### `registry`

* Default: "https://registry.npmjs.org/"
* Type: URL

The base URL of the npm registry.

<!-- automatically generated, do not edit manually -->
<!-- see lib/utils/config/definitions.js -->

<!-- AUTOGENERATED CONFIG DESCRIPTIONS END -->

### See Also

* [npm config](/cli/v8/commands/npm-config)
* [npmrc](/cli/v8/configuring-npm/npmrc)
* [npm adduser](/cli/v8/commands/npm-adduser)
