<div align="center">

<img src="./bahriya-logo.svg" alt="Bahriya" width="280" />

# Bahriya

**Distributed cloud infrastructure, without the ceremony.**

[Website](https://bahriya.cloud) · [Console](https://console.bahriya.cloud) · [Knowledgebase](https://bahriya.cloud/knowledgebase) · [Blog](https://bahriya.cloud/blog)

</div>

---

Bahriya is a container cloud with a simple contract: **bring a container image, pick your regions, and the platform runs it.** Load balancing, TLS, health checks, autoscaling, a secrets vault and managed datastores are included rather than bolted on — so shipping to production looks like shipping, not like assembling a platform first.

Everything has three front doors, all first-class from day one: the [console](https://console.bahriya.cloud), the [Reis CLI](https://bahriya.cloud/product/cli), and [Terraform](https://bahriya.cloud/product/terraform). Whatever you can click, you can script and you can declare.

## The platform

| Product | What it gives you |
| ------- | ----------------- |
| [HTTP Containers](https://bahriya.cloud/product/containers) | Deploy an image, get a TLS-terminated, autoscaling, multi-region service with custom hostnames. |
| [Workers](https://bahriya.cloud/product/workers) | Long-running background processes — queue consumers, stream processors — without ingress. |
| [Cron Jobs](https://bahriya.cloud/product/cronjobs) | Scheduled containers on a cron expression you control. |
| [Managed Valkey](https://bahriya.cloud/product/valkey) | The Redis-compatible, open-source in-memory datastore — single, highly available or sharded. |
| [Managed Memcached](https://bahriya.cloud/product/memcached) | Zero-ceremony caching next to your containers. |
| [Vault](https://bahriya.cloud/product/vault) | Secrets, TLS bundles, SSH/GPG keypairs and encryption keys — versioned, rotatable, mountable. |
| [Configs](https://bahriya.cloud/product/configs) | Env files and YAML/JSON/plain config files, attached to projects and mounted into containers. |
| [Network Policies](https://bahriya.cloud/product/network-policies) | Declare which workloads may talk to what, ingress and egress. |
| [Volume Storage](https://bahriya.cloud/product/volume-storage) | Persistent volumes for stateful workloads. |

## On GitHub

- [**terraform-provider-bahriya**](https://github.com/bahriya-cloud/terraform-provider-bahriya) — the official Terraform provider, published to the [Terraform Registry](https://registry.terraform.io/providers/bahriya-cloud/bahriya) as `bahriya-cloud/bahriya`. Every Bahriya resource, declaratively.

## Learn

- [Getting started](https://bahriya.cloud/knowledgebase/getting-started) and [quickstarts](https://bahriya.cloud/knowledgebase/quickstarts) — from zero to a running service.
- [Terraform guides](https://bahriya.cloud/knowledgebase/terraform) — a per-resource guide with a complete, working deploy example.
- [Reis CLI guides](https://bahriya.cloud/knowledgebase/cli) — the same platform from your terminal, in flags or YAML.
- [The full knowledgebase](https://bahriya.cloud/knowledgebase) — topologies, networking, vault, billing, migrations and more.
- [The blog](https://bahriya.cloud/blog) — launch announcements and the developer series.

---

<div align="center">

Made by sailors of the container seas. ⚓ **[bahriya.cloud](https://bahriya.cloud)**

</div>
