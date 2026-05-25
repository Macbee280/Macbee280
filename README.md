<div align="center">

<pre>
┌──────────────────────────────────────────────────────────────────┐
│  ● ● ●   gabe@localhost: ~                                       │
├──────────────────────────────────────────────────────────────────┤
│ 1: profile  2: work  3: writing  4: photos  5: about             │
└──────────────────────────────────────────────────────────────────┘
</pre>

</div>

```
gabe@localhost:~$ whoami
gabriel dimartino — computer engineer · neuromorphic researcher
spokane, wa · finishing b.s. computer engineering at gonzaga · grad may 2026
```

```
gabe@localhost:~$ cat intro.md
```

I design analog spiking-neuron circuits in 130nm BiCMOS, write the EDA tools
to lay them out, and run a 12-node neuromorphic compute cluster I built in
my apartment. Also: federated identity infrastructure for nonprofits, smart-
metering sensor boards for utility companies, and occasionally a coffee
machine FSM in SystemVerilog when a class demands it.

The full portfolio lives at **[gabedimartino.com](https://gabedimartino.com)**.

---

```
gabe@localhost:~$ ls -lh work/  # selected, recent first
```

| year   | project | what it is | status |
|--------|---------|------------|--------|
| 2026   | **[NeuroMatrix](https://gabedimartino.com/work/neuromatrix)** | 25,100-neuron hierarchical SNN validated in IHP SG13G2 130nm BiCMOS. 96% of Hopfield capacity, 82% cued recall. | `MWSCAS 2026 paper · submitted` |
| 2025–  | **[Fabrica](https://gabedimartino.com/work/fabrica)** | Three-tier analog EDA framework (behavioral → EKV 2.6 → PSP 103.6) sharing one Circuit IR. C++/Rust/Python. | `active · 345+ tests` |
| 2024–  | **[Ensemble Identity](https://gabedimartino.com/work/ensemble)** | Multi-tenant OAuth/OIDC platform on SvelteKit + Cloudflare Workers + D1. 8,319 users across 650+ cultural orgs. | `production` |
| 2025   | **[EN-59](https://gabedimartino.com/work/en-59)** | Universal sensor board for smart utility metering. Sub-2 µA quiescent, Apollo3 Blue BGA, 4-layer mixed-signal. | `in mfg · Itron capstone` |
| 2024–  | **[NCS Cluster](https://gabedimartino.com/work/ncs-cluster)** | 12-node neuromorphic compute cluster in my apartment. 12U rack, ~600W under load. | `ongoing · home-built` |

Full archive: **[gabedimartino.com/work](https://gabedimartino.com/work)**

---

```
gabe@localhost:~$ man gabe
```

```
NAME       gabe — computer engineer, neuromorphic researcher

WHAT I DO
  HARDWARE   analog VLSI · subthreshold CMOS · Mead-style LIF neurons
             4-layer mixed-signal PCB · BGA fanout · OrCAD Allegro
             IHP SG13G2 PDK · EKV 2.6 + PSP 103.6 compact models

  TOOLCHAIN  EDA framework design · sparse linear solvers (ILU+BiCGSTAB)
             analytic Jacobians · BDF-2 transient integration
             C++ numerical kernels · Rust orchestration · Python UX

  SYSTEMS    multi-tenant OAuth/OIDC · SvelteKit · Cloudflare Workers/D1
             multi-cloud resilience (AWS/GCP/Azure) · Kubernetes
             5,000+ endpoint enterprise networks · Cisco · Aruba · Juniper

  PROCESS    verification-first thinking · UVM-style testbench methodology
             cross-tier consistency tests · reference-model scoreboards

WHAT I'M
LEARNING    formal verification · DAE-split methods for stiff systems
             advanced subthreshold MOSFET modeling

CURRENTLY   finishing senior year · MWSCAS paper revisions · EN-59 bring-up
            pending · grad school decisions in the next few weeks

CONTACT     gdimartino@gabedimartino.com · gabedimartino.com
```

---

```
gabe@localhost:~$ cat now.md  # what i'm doing right now
```

The most current snapshot of what I'm working on lives at **[gabedimartino.com/now](https://gabedimartino.com/now)** — updated when the answer changes meaningfully, which is more often than you'd think.

Recent writing lives at **[gabedimartino.com/writing](https://gabedimartino.com/writing)**.

---

```
gabe@localhost:~$ ls -lh elsewhere/
```

- **website** · [gabedimartino.com](https://gabedimartino.com) — the full portfolio (this README is the short version)
- **email** · gdimartino@gabedimartino.com — I answer
- **linkedin** · [linkedin.com/in/gdimartino](https://linkedin.com/in/gdimartino)
- **scholar** · pending — first paper under review

---
```
gabe@localhost:~$ tail -n 1 .bashrc
# 'Broadcasting from my room and playing with my toys'
```
