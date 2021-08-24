[![Delivery](https://github.com/amendoa/action-setup-consul-template/actions/workflows/delivery.yml/badge.svg)](https://github.com/amendoa/action-setup-consul-template/actions/workflows/delivery.yml)

# Setup consul-template

This action provides the ability to install `consul-template` cli on your github actions Workflow

_:raised_hand_with_fingers_splayed: Only for linux and macOS runners_

## Inputs

| Name    | Description                        | Type     | Required |
| ------- | ---------------------------------- | -------- | -------- |
| version | consul-template version to install | `number` | `false`  |

## Usage

```yml
steps:
  - uses: amendoa/action-setup-consul-template@v1
    with:
      version: 0.27.0
```

## How to contribute?

Check out the [contributor guide](/CONTRIBUTING.md).
