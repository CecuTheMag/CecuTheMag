### I build infrastructure that isn't supposed to be possible from a bedroom.

A messenger with no servers. A supercomputer made of school browsers. An AED map that talks you through CPR while the ambulance is on its way.

17, Stara Zagora, Bulgaria. I write the systems code, ship the apps, and sell the product myself.

---

#### Shipping

**[Kant](https://github.com/CecuTheMag/Kant)** &nbsp;·&nbsp; [kant.network](https://kant.network)
End-to-end encrypted messenger with no phone number and no one in the middle. Messages go device to device over libp2p; relays carry only ciphertext they can't read. X3DH and the Double Ratchet on libsodium. Linux, Windows, macOS, Android and iOS clients from one TypeScript monorepo, and anyone can run a relay from home without opening a port.
`v0.6.0 beta` &nbsp; `~33k lines` &nbsp; `AGPL-3.0`

**Swarm** &nbsp;·&nbsp; *private until demo day*
A volunteer supercomputer built from the idle browsers in a school. Open a page and your phone becomes a compute node running sandboxed WebGPU and WebAssembly work. The Rust coordinator schedules jobs across unreliable devices that come and go, and assumes some of them lie: results are checked by redundancy and spot checks. First real workload is a school timetable solver. Measured bit-exact against the Rust reference on Adreno GPUs, with a CPU fallback for machines WebGPU won't run on.
`Rust` &nbsp; `WebGPU` &nbsp; `~20k lines` &nbsp; `Chromium · Firefox · WebKit tested`

**[ДефиКарта](https://github.com/CecuTheMag/Defikarta)**
Finds the nearest defibrillator in Stara Zagora, gets you to call 112, and guides you through hands-only CPR. Native iOS and Android, an offline-capable PWA, and a dispatcher console that pages nearby trained responders. Every point on the map is a real, sourced AED. The ranking, dispatch and CPR logic sit in one shared core, so every app makes the same call.
`Expo` &nbsp; `React` &nbsp; `Leaflet` &nbsp; `OSM`

**Findr** &nbsp;·&nbsp; *B2B, private*
An AI study advisor built to be sold to universities as a one-tag embed. It answers from 2,215 programmes at 230 German universities held in its own Postgres, not someone else's vector store, so retrieval is free, fast and auditable. Separate app and admin stacks with nothing shared but key verification, and metering per partner.
`Node` &nbsp; `Postgres` &nbsp; `LLM agents` &nbsp; `Docker`

---

#### Also built

| | |
|---|---|
| **[Buttonwood](https://github.com/CecuTheMag/Buttonwood)** | Self-hosted Telegram trading companion for Solana: paper trading on live quotes, whale following with token safety checks |
| **advDash** | Fleet control for browser automation: one container per account, each with a real Chromium behind its own proxy |
| **[Doug](https://github.com/CecuTheMag/DougWeb)** | Low-latency AI call assistant that screens your incoming calls |
| **[SchoolSync](https://github.com/CecuTheMag/SchoolSync)** | Inventory management for schools |
| **[DSM](https://github.com/CecuTheMag/DSM-Discord-Bot)** | Modular Discord bot for moderation, tickets and verification |

---

#### Business

I co-run **Placet**, a two-person agency. We get suspended Google listings back for small businesses (paid only once the listing is live again) and review founders' codebases before they launch.

---

#### Stack

**Systems** &nbsp; Rust · TypeScript · Python · WebAssembly · WGSL
**Networking & crypto** &nbsp; libp2p · libsodium · WebSockets · SSE
**Product** &nbsp; React · React Native / Expo · Electron · Vite
**Infra** &nbsp; Postgres · Docker · Caddy · Supabase · Vercel · GitHub Actions

---

Building something hard? &nbsp;[magcecu@gmail.com](mailto:magcecu@gmail.com) &nbsp;·&nbsp; [kant.network](https://kant.network)
