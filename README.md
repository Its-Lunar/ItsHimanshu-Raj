# Himanshu Raj

Systems and security engineer building low-overhead desktop defense, hardened process enclaves, and private networking infrastructure in Rust.

Founder of [The Lunar Org](https://github.com/The-Lunar-Org). Currently: engineering **Specter**, a zero-trust endpoint containment runtime with kernel-level packet inspection, Windows Job Object sandboxing, and userspace WireGuard mesh routing.

---

## Systems & Architecture

- **Endpoint containment:** Windows Job Object confinement, suspended-spawn process interception, token deprivation, and dynamic descendant tracking.
- **Encrypted transport & networking:** Userspace WireGuard tunnels, DNS-over-HTTPS resolution, and active egress route verification.
- **Local IPC & authorization:** Named pipes protected by per-user security descriptors (DACLs) and constant-time caller executable hash verification.
- **Security primitives:** DPAPI-backed encrypted credential vaults, Authenticode binary signature enforcement, and zero-telemetry operational security.

---

## Shipped Work

**[Specter](https://github.com/The-Lunar-Org/be-safe)**
Hardened client defense runtime. Implements hardware identity virtualization, background sensor gates (microphone/camera/clipboard), and isolated application enclaves with continuous integrity tripwires. Built with a Rust enforcement core and a lightweight Tauri shell.

**[Cloudflare Update Proxy](https://github.com/The-Lunar-Org/be-safe/tree/specter-rewrite/infra/cloudflare-update-worker)**
An authenticated edge worker proxying signed release assets, update manifests, and differential binary payloads from private GitHub infrastructure directly to desktop clients.

---

## Core Stack

Rust, C, TypeScript, Tauri, Win32 API, WireGuard, PowerShell, GitHub Actions CI/CD

---

## Contact

- Org: [The Lunar Org](https://github.com/The-Lunar-Org)
- GitHub: [@ItsHimanshu-Raj](https://github.com/ItsHimanshu-Raj)
- X: [@1tsRaj](https://x.com/1tsRaj)
- Web: [1tsraj.workers.dev](https://1tsraj.workers.dev)
