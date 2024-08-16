---
title: Konnect Installation & Configuration
meta_desc: Information on how to install the Konnect provider.
layout: installation
---

## Installation

The Pulumi Konnect provider is available as a package in all Pulumi languages:

* JavaScript/TypeScript: [`@pulumiverse/konnect`](https://www.npmjs.com/package/@pulumiverse/konnect)
* Python: [`pulumiverse_konnect`](https://pypi.org/project/pulumiverse_konnect/)
* Go: [`github.com/ZachAndrews98/pulumi-konnect/sdk/go/konnect`](https://pkg.go.dev/github.com/ZachAndrews98/pulumi-konnect/sdk/go/konnect)
* .NET: [`Pulumiverse.Konnect`](https://www.nuget.org/packages/Pulumiverse.Konnect)


## Configuration

> Note:  
> Replace the following **sample content**, with the configuration options
> of the wrapped Terraform provider and remove this note.

The following configuration points are available for the `konnect` provider:

- `konnect:apiKey` (environment: `konnect_API_KEY`) - the API key for `konnect`
- `konnect:region` (environment: `konnect_REGION`) - the region in which to deploy resources

### Provider Binary

The Konnect provider binary is a third party binary. It can be installed using the `pulumi plugin` command.

```bash
pulumi plugin install resource konnect <version>
```

Replace the version string `<version>` with your desired version.
