# anolis-provider-hello-python

An [Anolis](https://github.com/anolishq/anolis) device provider generated from
[anolis-provider-template-python](https://github.com/anolishq/anolis-provider-template-python)
on a personal account, outside the anolishq organisation. It is the template's
simulated heater, renamed with `scripts/rename.sh hello-python` and otherwise
unchanged.

It exists as evidence that a provider started from the template:

- builds, passes the conformance harness and releases in an account that has
  none of anolishq's secrets, apps, rulesets or reusable workflows;
- installs on a machine through an unchanged `install.sh` and
  `anolis-workbench provider import --repo`, pinned from this account.

Once that is recorded, this repository is archived: read-only, with its
releases still downloadable.

## Install

```yaml
components:
  providers:
    hello-python:
      repo: CameronBrooks11/anolis-provider-hello-python
      version: "0.1.0"
```

The device, its config and its functions are the template's; see its
[README](https://github.com/anolishq/anolis-provider-template-python#the-device).

## Licence

Apache-2.0.
