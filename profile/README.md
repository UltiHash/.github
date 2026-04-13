<div align="center">

<img src="https://cdn.prod.website-files.com/63d6aca49010ac629c2c5622/653ba1d36b1028818bf9d2a9_Asset%206.svg" alt="UltiHash" height="52" />

### High-performance object storage for AI and data-intensive workloads.

S3-compatible · Binary-level deduplication · Kubernetes-native · Apache 2.0

[Website](https://ultihash.io) · [Docs](https://docs.ultihash.io) · [Discord](https://ultihash.io/community)

</div>

---

**UltiHash Core** is an open-source object storage system that eliminates redundant data at the binary level — across all objects, all formats, continuously. It speaks S3, deploys on Kubernetes via Helm, and reduces storage requirements by up to 60% on typical AI datasets without any changes to your application.

| Repository | What it is |
|---|---|
| [core](https://github.com/UltiHash/core) | The storage engine — C++, CMake, Apache 2.0 |
| [uh-helm](https://github.com/UltiHash/uh-helm) | Helm chart for Kubernetes deployment |
| [uh-documentation](https://github.com/UltiHash/uh-documentation) | Source for [docs.ultihash.io](https://docs.ultihash.io) |
| [scripts](https://github.com/UltiHash/scripts) | Integration examples — PySpark, Trino, Airflow, boto3 and more |
| [core-tests](https://github.com/UltiHash/core-tests) | Integration test suite |

**Try it in 60 seconds** — no account needed:

```bash
curl -fsSL https://ultihash.io/1line | bash
```

Spins up a local Docker cluster, lets you point it at any directory, and shows you the deduplication savings in your terminal.

---

<div align="center">
  Made in Berlin &nbsp;·&nbsp; <a href="https://ultihash.io">ultihash.io</a> &nbsp;·&nbsp; <a href="https://ultihash.io/community">Join us on Discord</a>
</div>
