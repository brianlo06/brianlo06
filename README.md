## Hi, I'm Brian!

Computer Engineering student at **Rutgers** (class of 2028). I like building systems where the result can be *proven* correct: hardware checked exhaustively against an independent model, network code tested under deterministic injected faults, and software that runs on real devices instead of just in a demo.

**Looking for Summer 2027 internships** in hardware, embedded, or systems software.

`C++20` · `Python` · `Swift` · `TypeScript` · `SystemVerilog` · `Linux / epoll` · `Yosys / nextpnr` · `PostgreSQL` · `Cloudflare Workers`

---

### 🔧 Hardware & systems

| Project | What it does |
| --- | --- |
| **[circuit-to-silicon](https://github.com/brianlo06/circuit-to-silicon)** | Gate netlist → generated SystemVerilog → FPGA primitives. Each stage is proven equivalent to an independently written Boolean model by exhaustive simulation, including the post-synthesis mapped netlist. 337 tests. |
| **[netfault-lab](https://github.com/brianlo06/netfault-lab)** | Linux/C++20 `epoll` TCP proxy for reproducing failure behavior: bounded buffers with watermarks, half-close propagation, seeded fault injection (latency, rate limits, resets), sanitizer-verified tests. [Replay real runs in the browser →](https://netfault-lab.pages.dev) |
| **[circuit-classifier](https://github.com/brianlo06/circuit-classifier)** | Recognizes digital logic circuits from schematic images: YOLO symbol detection, wire-topology extraction and circuit-graph analysis. |
| **[airpoint](https://github.com/brianlo06/airpoint)** | Turns a phone into a motion-controlled remote for a Mac: gyroscope sensor fusion, TLS + pairing, a WebSocket input protocol, and a menu-bar app. Two games are built on its stack: **[reticle](https://github.com/brianlo06/reticle)** (light-gun) and **[ricochet](https://github.com/brianlo06/ricochet)** (tanks). |

### 🧠 Software & research

| Project | What it does |
| --- | --- |
| **[keelson](https://github.com/brianlo06/keelson)** | Personal LLM memory architecture built on three primitives: an immutable transcript, supersession-based claims, and a provenance score. Benchmarked with **[pmem-bench](https://github.com/brianlo06/pmem-bench)**, a hand-labeled extraction benchmark with an LLM judge. |
| **[datum](https://github.com/brianlo06/datum)** | Registry for parametric CAD parts. You publish the source, it compiles in a sandbox, the geometry gets measured, and parts that don't build are rejected. |
| **[ulam-research](https://github.com/brianlo06/ulam-research)** | Experimental-math paper on the Ulam sequence's hidden signal, with four new results including a "one-third law". |
| **[digital-footprint-tracker](https://github.com/brianlo06/digital-footprint-tracker)** | Privacy-first platform for seeing your own public online presence: encrypted identifiers, consent, a durable PostgreSQL job queue, tenant isolation. |

### 🎮 Live and playable

- **[Worldview](https://jarvisworlds.com)**: a live 3D globe of world news events ([frontend](https://github.com/brianlo06/worldview) · [API](https://github.com/brianlo06/worldview-api))
- **[Dungeon Pact](https://dungeon-pact.violarage10.workers.dev)**: co-op tactical roguelite for 2–4 players with a shared treasury ([code](https://github.com/brianlo06/dungeon-pact))
- **[Chaos Chess](https://chaos-chess.violarage10.workers.dev)**: chess where you draft random piece upgrades, playable solo, local or online ([code](https://github.com/brianlo06/chaos-chess))
- **[LikeThisSong](https://lts.jarvisworlds.com)**: find a song from a YouTube link and discover similar music
