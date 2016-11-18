---
title: CLI commands overview
---

## CLI commands overview

```console
snyk [options] [command] [package]
```
The package argument is optional. If no package is given, Snyk will run the command against the current working directory allowing you test you non-public applications.

### Commands

```console
auth [api-token].....sign into snyk.
test ............... test for any known vulnerabilities.
wizard ............. configure your policy file to update, auto patch and ignore vulnerabilities.
protect ............ protect your code from vulnerabilities and optionally suppress specific vulnerabilities.
monitor ............ record the state of dependencies and any vulnerabilities on snyk.io.
policy ............. display the Snyk policy for a package.
```

### Options

```console
--dev .............. include devDependencies (defaults to production only)
--ignore-policy .... ignores and resets the state of your policy file
--trust-policies ... applies and uses ignore rules from your dependencies's Snyk policies,
                     otherwise ignore policies are only shown as a suggestion.
--dry-run .......... don't apply updates or patches during protect.
-q, --quiet ........ silence all output.
-h, --help ......... this help information.
-v, --version ...... the CLI version.
```

### Examples

```console
snyk test
snyk test ionic@1.6.5
```

<p class="layout-aside backdrop-glowing u--push-bottom-l u--push-top-l">
  Use <code>snyk test</code> in your test scripts. If a vulnerability is found, the process will exit with a non-zero exit code.
</p>
