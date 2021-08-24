[![Delivery](https://github.com/amendoa/action-setup-consul-template/actions/workflows/delivery.yml/badge.svg)](https://github.com/amendoa/action-setup-consul-template/actions/workflows/delivery.yml)

# Setup consul-template

This action provides the ability to setup your Github Actions workflow with a specific version of [consul-template](https://github.com/hashicorp/consul-template) CLI

_:raised_hand_with_fingers_splayed: Only for linux and macOS runners_

## Inputs

| Name    | Description                        | Type      | Example | Required |
| ------- | ---------------------------------- | --------- | ------- | -------- |
| version | consul-template version to install | `numeric` | 0.27.0  | `false`  |

## Usage

```yml
steps:
  - uses: amendoa/action-setup-consul-template@v1
    with:
      version: 0.27.0
```

## How to contribute?

Check out the [contributor guide](/CONTRIBUTING.md).
