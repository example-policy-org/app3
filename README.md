# App3

> This app is compliant with version [1.1.0](https://github.com/example-policy-org/policy/releases/tag/1.1.0) of the company policy but its only using [1.0.0](https://github.com/example-policy-org/policy/releases/tag/1.0.0) and can be updated with a pull-request.

## Test policy locally

```bash
$ docker run --rm -ti -v $(pwd):/apps ghcr.io/example-policy-org/policy-checker

Checking policy version...
Policy version: 1.0.0
Fetching Policy...

Applying 1 policy to 1 resource...
(Total number of result count may vary as the policy is mutated by Kyverno. To check the mutated policy please try with log level 5)

pass: 1, fail: 0, warn: 0, error: 0, skip: 0
```
