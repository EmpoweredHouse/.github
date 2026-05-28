# EmpoweredHouse

> Software shaped to your company.

EmpoweredHouse is the runtime that turns your process into your software.

Every company runs on software it did not write. That was the strange compromise the last twenty years asked us to accept: you pick the CRM your sales team has to bend around, the ERP your operations team has to apologize for, stitch them together with integrations and a quiet line item called consulting, and then call the result your business. It is not. It is a costume your business wears.

AI just made the alternative real. The cost of bespoke code collapsed from quarters to hours. Configuration is now the expensive path. Generation is the cheap one. The whole stack is upside down.

We are the runtime that makes shaped software the default, not the luxury. Generated, not configured. Owned, not licensed. Built in public.

**[Read the manifesto →](https://github.com/EmpoweredHouse/.github/blob/main/profile/Manifest.md)**

---

> You shouldn't fit your company to the software.

---

### Shape. See. Run.

The offer is one lifecycle in three beats.

You **shape** the software your company runs on, inside a runtime that takes command of governance, compliance, security, and execution.

You **see** your company in motion through an intelligence layer that knows what its objects mean: [shugyo.ai](https://shugyo.ai).

Your business **runs** on what you shaped, in code you own.

The substrate that makes the first beat possible is what this organization is building, in public. The second beat lives at shugyo.ai. The third lives at your company.

---

### Where we are today

We are early. The runtime is being built in public, in pieces. Two repositories carry the work so far:

| Repository | What it does |
|---|---|
| [`process-native-starter`](https://github.com/EmpoweredHouse/process-native-starter) | The `pns` CLI that bootstraps a Process Native project. Generates a Phoenix umbrella with LiveView and LiveReact, wires the AI engineering harness (progressive-disclosure AGENTS.md, decision records, GSD workflows, community skills), and ships with CI quality gates (Credo, ESLint, Sobelow, Dialyzer, coverage, E2E). The substrate the bespoke layer is built on. |
| [`accrete`](https://github.com/EmpoweredHouse/accrete) | Compound knowledge for AI-native development. Decision records (SDR, PDR, ADR) as version-controlled, MCP-searchable infrastructure backed by a Kuzu graph database. Each decision makes the next decision easier. The context-engineering layer for agents and humans. |

[Shugyo](https://shugyo.ai) is the intelligence layer over the running business. Sold as product, not open here. Its signal contract and integration points will land in this org as the ecosystem matures.

The remaining layers of the runtime (a standalone primitives library, runtime observability as its own package, the process repository tooling, the process-mapping playbook as a published package) are incubating. Watch this org, or talk to us if you need them sooner.

---

### Quick start

```bash
bun install
bun run build
bun link

pns init \
  --project-slug my-app \
  --otp-app my_app \
  --module-name MyApp \
  --product-name "My App" \
  --client-name "Client Name"
```

You get a Phoenix project with the harness in place, decision records wired through `accrete`, and the GSD workflow ready to plan and execute the foundation milestone. See the [QUICKSTART](https://github.com/EmpoweredHouse/process-native-starter/blob/main/QUICKSTART.md) for the full path.

A competent technology leader should be able to land here, run `pns init`, and ship the first slice without ever talking to us. If that is not true, we are holding the open source hostage.

---

### The default stack

Elixir and Phoenix. The runtime, the team's training, and our recruiting pipeline are aligned to it. `process-native-starter` encodes the default: Phoenix umbrella + LiveView + LiveReact + React 19 + Tailwind v4 + ShadCN, with the harness wired in. A different stack is accepted only when a hard constraint demands it. The burden of proof sits with the deviation, not with the default.

We pick the default deliberately. An ecosystem becomes a sequence of unrelated custom projects the moment the stack is chosen engagement-by-engagement.

---

### Who this is for

Engineers who can pair with a CFO, a COO, or a head of operations and shape a primitive in the room. Senior product engineers, DDD practitioners, AI engineers who think in business terms before code. SRE-grade platform engineers who treat the runtime as production from day one. Designers who work on workflow surfaces and exception flows, not marketing pages.

Companies whose process is genuinely theirs and whose owner is in the room. If your process is generic, buy SaaS. If your team will not engage with the mapping, do not start. Disqualification is a feature.

---

### Working with us

The open source is the substrate. The commercial work sits next to it.

**Shugyo** ([shugyo.ai](https://shugyo.ai)) is the intelligence layer: a living digital twin of the organization, grounded in the data the business already has. It shows where things break, what they cost, who is blocked, and what to decide next. Sold on its own pricing model.

**Services** are the premium layer: process mapping, the build of the first slices, the integration work, the domain modelling, the hard cases where business processes are tangled and the answer is not in any playbook. We do not compete with the open source. We are the partner of choice for the work the open source assumes someone is doing.

Per-process or per-engagement. No per-user SaaS pricing.

---

### Contributing

Open by default, private by exception. Patterns extracted from engagements ship back here once anonymised: scaffold improvements, new primitives, runtime gaps closed, monitoring rules, playbook updates. Sector patterns belong here too: a logistics exception-handling pattern, a fintech compliance pattern, a manufacturing reconciliation pattern.

Contribution model and license details are repository-specific. See each repo's `CONTRIBUTING.md`. `accrete` ships under MIT. The `process-native-starter` license is being finalised.

---

### Brand family

EmpoweredHouse is the brand for the runtime and the work that surrounds it. It sits alongside [Appunite](https://appunite.com) (the agency the runtime came out of) and [Shugyo](https://shugyo.ai) (the intelligence layer).

---

### Find us

- Site: [empowered.house](https://empowered.house)
- Intelligence layer: [shugyo.ai](https://shugyo.ai)
- Contact: empowered@appunite.com
