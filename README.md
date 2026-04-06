# AI Factories & GPU Infrastructure — Master List 2026

> Comprehensive reference of neoclouds, sovereign AI clouds, telco AI factories, and alternative GPU infrastructure providers. Cross-referenced with the [Datum Cloud awesome-alt-clouds](https://github.com/datum-cloud/awesome-alt-clouds) list. Updated via AI-assisted research.

**Legend:**
- 🟢 = Operational / Live
- 🟡 = Under construction / 2026 delivery  
- 🔵 = Planned / early stage
- ◆ = Listed on Datum awesome-alt-clouds
- 📡 = Telco-led sovereign AI factory

---

## Tier 1 — Hyperscale Neoclouds (Multi-GW Pipeline)

| Company | HQ | GPU Types | Live MW | Pipeline | Key Notes |
|---|---|---|---|---|---|
| **CoreWeave** (CRWV) | NJ, USA | H100, H200, A100, GB200 | 🟢 850 MW | 3.1 GW contracted; 43 DCs; $55.6B backlog | Market leader; OpenAI $12B, Meta $14B, NVIDIA $6.3B; $12–13B 2026 rev guided |
| **Nebius Group** (NBIS) ◆ | Amsterdam, NL | H100, H200, GB300 | 🟢 170–220 MW | 2.5–3 GW; Finland 310MW, France 240MW, Missouri 1.2GW | Microsoft $17–19B + Meta $27B; $7–9B ARR target 2026; NVIDIA $2B investment |
| **Lambda Labs** | San Francisco, USA | H100, H200, B200, GB300 NVL72 | 🟢 ~320 MW | 3 GW by 2030 | $2.3B raised; NVIDIA $1.5B leaseback 18K GPUs; Microsoft multi-B contract |
| **Crusoe Energy** ◆ | Denver, USA | H100, GB200 NVL72 | 🟢 ~400 MW | 45 GW pipeline; OpenAI Abilene 1.2GW campus | $10B+ valuation; NVIDIA + Founders Fund; Stargate flagship; sustainable compute |
| **Nscale** | London, UK | NVIDIA GB300 (~200K GPUs) | 🟡 ~50–100 MW | TX 240MW→1.2GW; Norway 230MW; UK 90MW; Portugal 50MW | NVIDIA-backed $1.1B; Microsoft 200K GB300 contract; Stargate Norway; UK govt-championed |

---

## Tier 2 — Scaled Operators / Publicly Traded Pivots

| Company | HQ | GPU / Model | Live MW | Pipeline | Key Notes |
|---|---|---|---|---|---|
| **IREN / Iris Energy** (IREN) | Australia | H100, H200 | 🟢 ~50 MW AI | 2.9 GW contracted; 140K GPUs by EOY26 | Microsoft $9.7B 5-yr; West Texas; $3.4B AI ARR target |
| **Hut 8** (HUT) | Miami, USA | Hosted / colocation | 🟢 1,020 MW managed | 330 MW under construction; 1.23 GW in dev | Fluidstack $7B 15-yr / 245 MW Louisiana (Google-backed); +1 GW ROFO option |
| **Applied Digital** (APLD) | Dallas, USA | Hosted / colocation | 🟢 ~100 MW HPC | 400 MW+ committed | CoreWeave 400 MW lease ($7B); North Dakota + Texas sites |
| **TeraWulf** (WULF) | Easton, MD, USA | Hosted / colocation | 🟢 ~50 MW HPC | 168 MW JV + 250–500 MW pipeline | Fluidstack JV $9.5B 25-yr / 168 MW Texas; 80-yr Cayuga lease |
| **Cipher Mining** (CIFR) | New York, USA | Colocation host | 🟡 AI rev Aug 2026 | ~500 MW committed | AWS ~$5.5B; Fluidstack (Google-backed) ~$3B; $8.5B total AI/HPC contracted |
| **Core Scientific** | Austin, USA | H100, colocation | 🟢 ~200 MW HPC | ~500 MW pipeline | CoreWeave colo deals; HPC pivot from Bitcoin mining |
| **WhiteFiber** (WYFI) | USA | GPU cloud | 🟢 — | Publicly traded neocloud | +179% NTM revenue growth expected |
| **FluidStack** | London, UK | H100, H200 | 🟢 400+ MW via JVs | Anthropic $50B; Hut8 $7B; TeraWulf $9.5B; Cipher $3B | Critical GPU infra intermediary; wholesale + marketplace |

---

## Tier 3 — Enterprise / Mid-Market GPU Clouds

| Company | HQ | GPU Types | Scale | Focus |  |
|---|---|---|---|---|---|
| **Vultr** | West Palm Beach, USA | H100, A100, L40, B200, GH200 | 32 global regions | Global multi-region; enterprise + edge; Digital Realty partnership | |
| **TensorWave** ◆ | USA | AMD MI300X, MI325X, MI350X | 🟡 1 GW target | AMD-native neocloud; world's largest planned AMD GPU cluster; Ultra Ethernet | |
| **Voltage Park** | San Francisco, USA | H100 SXM5, 3.2 Tbps InfiniBand | — | Deep AI cluster engineering; 3.2 Tbps IB; single-tenant superclusters | |
| **Hyperstack / NexGen** ◆ | UK / Norway | H100 SXM, A100, L40S | 350 Gbps networking | Green cloud EU + North America; NVLink; ~$1.90/hr H100 | |
| **Gcore** ◆ | Luxembourg | H100, A100, L40S | 180+ PoPs; 50+ cloud locations | EU sovereign + global edge; CDN-integrated; DDoS-resilient | |
| **Genesis Cloud** ◆ | Munich, Germany | HGX H100, GB200 NVL72 | EU multi-site | EU sovereign; GDPR; renewable energy; LLM training | |
| **OVHcloud** | Roubaix, France | H100, A100, L40S | EU multi-region | SecNumCloud certified; single-tenant GPU; French govt; EU's largest independent cloud | |
| **DataCrunch / Verda** ◆ | Helsinki, Finland | H100, A100 | 100% renewable | Nordic renewable; EU data sovereignty; GDPR-compliant | |
| **Together AI** | San Francisco, USA | H100, A100 | — | Open-source LLM training + inference; inference-optimized stack | |
| **Paperspace (DigitalOcean)** | New York, USA | H100, A100, RTX | — | MLOps platform + GPU cloud; $111M acquisition 2023; developer-first | |
| **Civo** ◆ | UK | GPU + Kubernetes | Multi-region | Simple cloud + K8s; developer-focused; transparent pricing | |
| **Anyscale** ◆ | San Francisco, USA | Multi-GPU, Ray-native | — | Distributed computing on Ray; managed Ray clusters; AI/Python scaling | |
| **IONOS Cloud** ◆ | Germany | GPU cloud, bare metal | EU multi-region | Public + bare metal + managed K8s; European data residency | |
| **Hetzner** ◆ | Germany | A100, H100 (limited) | EU + US regions | Cost-efficient EU cloud; bare metal + VPS; popular with EU ML teams | |
| **Linode (Akamai)** ◆ | Cambridge, MA, USA | GPU instances | Global | Developer-friendly; Akamai-owned; edge + cloud compute | |
| **DigitalOcean** ◆ | New York, USA | H100, A100 | Global | Simplicity + scalability; owns Paperspace; SMB + developer-first | |
| **Atlantic.net** ◆ | Orlando, USA | H100 NVL, L40S | 8 global DCs | 100% uptime SLA; HIPAA, PCI, SOC2, GDPR; bare-metal GPU; NVIDIA NCP | |
| **GMI Cloud** ◆ | USA | H100, A100 | — | GPU cloud for AI/deep learning; self-service; competitive pricing | |
| **Hyperbolic** ◆ | USA | H100, A100 | — | Scalable GPU compute; performance + cost focus | |
| **NetActuate** ◆ | USA | GPU + bare metal | Global edge | Hybrid cloud + edge; BGP + anycast expertise | |
| **Latitude.sh** | São Paulo, Brazil | H100, bare metal | 18+ global locations | Bare metal + GPU Accelerate; Terraform provider; fast deploy | |
| **Hivelocity** ◆ | Tampa, USA | GPU + bare metal | US multi-site | Experienced VPS + bare metal; enterprise hosting; 30+ years | |
| **DataPacket** ◆ | USA / EU | Bare metal + GPU | Global | High-performance infra; DDoS scrubbing; bandwidth-intensive | |
| **Sharon AI** | Australia | NVIDIA (NCP partner) | 1,000+ DCs via Megaport | APAC-leading neocloud; colocation-first; global interconnection | |
| **Lyceum** ◆ | EU | GPU cloud | EU | EU-built and operated; developer + AI team focus; GDPR-native | |
| **Ubicloud** ◆ | San Francisco, USA | Bare metal | Multi-cloud | Open-source cloud; self-host or managed; IaaS features | |
| **Cycle.io** ◆ | USA | Container + GPU | — | Container orchestration; bare-metal + cloud; developer PaaS | |

---

## Tier 4 — Developer / Marketplace / Serverless / Budget GPU

| Company | HQ | GPU Types | H100 $/hr | Model |  |
|---|---|---|---|---|---|
| **RunPod** | USA | H100, A100, RTX 4090 | ~$2.49 | Secure Cloud + Community Cloud + Serverless inference | |
| **Vast.ai** | USA | H100, A100, consumer | ~$1.74 | Decentralized bidding marketplace; lowest-cost training; spot-style | |
| **SF Compute** | USA | H100 | ~$1.45 | Time-based reservations; no long-term contracts | |
| **Thunder Compute** | USA | H100, A100 | ~$0.78 | Instant VM spin-up; virtual GPU sharing; lowest entry-point | |
| **Modal** ◆ | USA | H100, A100 | Pay-per-use | Serverless; AI + data teams; no infra management; instant scale | |
| **Fal.ai** ◆ | USA | H100, A100 | Pay-per-use | Serverless GPU inference; image/video/audio model focus | |
| **Cerebrium** ◆ | USA | H100, A100 | Pay-per-use | Serverless GPU; ML model deploy; auto-scaling; cold-start optimized | |
| **Baseten** ◆ | USA | H100, A100 | Pay-per-use | Fast + reliable model inference; self-hosted + hybrid options | |
| **FriendliAI** ◆ | USA / South Korea | H100, multi | Pay-per-use | 2–3x inference speed; 490K+ models; 99.99% SLA | |
| **Cudo Compute** ◆ | UK | H100, A100, multi | Varies | Decentralized cloud GPU; distributed infra; sustainability focus | |
| **Aethir** ◆ | UAE | Enterprise GPUs | Varies | Distributed enterprise GPU; decentralized cloud compute; global | |
| **HydraHost** ◆ | USA | GPU compute | Budget | Affordable GPU; researchers + indie developers | |
| **Spheron** | USA | H100, A100, multi | Varies | Decentralized GPU aggregator; multi-provider billing; marketplace | |
| **Beam** ◆ | USA | GPU cloud | Pay-per-use | Cloud infra for high-performance apps; developer-focused | |
| **E2E Cloud** ◆ | India | H100, A100 | Budget | Indian GPU cloud; affordable AI/ML infra; IT Act compliance | |
| **exe.dev** ◆ | USA | VM + GPU | Pay-per-use | Modern VM; sub-second starts; built for AI coding agents | |

---

## Sovereign AI Clouds — European Telco-Led AI Factories

| Company | Nation | GPU / Compute | Scale | AI Cloud Product | Sovereign Mandate |
|---|---|---|---|---|---|
| **Deutsche Telekom** 📡 | 🇩🇪 Germany | NVIDIA DGX B200, RTX PRO (~10,000 GPUs) | 🟢 0.5 EFLOPS; Q1 2026 live | **Industrial AI Cloud** — world's first industrial AI cloud; Munich data center; €1B investment with NVIDIA; 1,000+ DGX B200 systems; 20 PB storage | Germany sovereign; GDPR + EU regulatory stack; customers include SAP, Siemens, Perplexity, Agile Robots; 50% increase in Germany's AI compute; digital twins via NVIDIA Omniverse; manufacturing, automotive, pharma, robotics focus |
| **Orange Business** 📡 | 🇫🇷 France | NVIDIA H100, Blackwell GPUs | 🟢 Live — EU-hosted | **Live Intelligence** — generative AI platform; sovereign, hosted in Europe; Cloud Avenue infrastructure; NVIDIA Cloud Partner (NCP) | France + Europe + Africa sovereign; 73,000 Orange employees using daily; 30,000+ AI requests/day; enterprise agentic AI; GDPR-compliant; B2B arm of Orange Group (290M+ customers) |
| **Telenor** 📡 | 🇳🇴 Norway | NVIDIA AI Enterprise, GPU cluster | 🟢 Live + expanding | **Norway's first sovereign AI cloud** — expanding with new renewable-energy AI DC; surplus energy fed back to grid; NVIDIA AI Enterprise + NIM microservices | Norway sovereign; Norwegian public sector, industrial automation, local language models; powers BabelSpeak multilingual AI; Norwegian Red Cross piloting; Capgemini as build partner |
| **Swisscom** 📡 | 🇨🇭 Switzerland | NVIDIA DGX SuperPOD, GPU cluster | 🟢 Live — Swiss AI Platform | **Swiss AI Platform + GenAI Studio** — enterprise AI agents; AI Work Hub; Model Catalog; sovereign AI factory on NVIDIA DGX SuperPOD | Switzerland sovereign; enterprise AI model customization + agentic AI; Swiss regulated industries (banking, insurance, healthcare); Swiss data residency guaranteed |
| **Telefónica** 📡 | 🇪🇸 Spain | NVIDIA GPUs (hundreds), NIM, AI Enterprise | 🟡 Piloting edge AI across Spain | **Distributed edge AI fabric** — AI inference at the edge; hundreds of NVIDIA GPUs across Spain; AI Enterprise + NIM microservices; low-latency inference | Spain sovereign; edge-first — data stays within national borders; priority sectors: government and financial services; 300M+ customer network as distribution backbone |
| **Fastweb (Swisscom/Italy)** 📡 | 🇮🇹 Italy | NVIDIA DGX AI supercomputer | 🟢 Live — Italy | **MIIA (Italian LLM) + sovereign AI cloud** — one of Italy's first Italian-language foundation models; runs on NVIDIA DGX supercomputer; end-to-end sovereign AI platform | Italy sovereign; Italian language model (MIIA) for generative AI; Italian public administration + enterprise; part of NVIDIA's European sovereign AI infrastructure program |

---

## Sovereign AI Clouds — Europe (Non-Telco)

| Company | Nation | GPU / Compute | MW Live | Pipeline | Sovereign Mandate |  |
|---|---|---|---|---|---|---|
| **Mistral Compute** | 🇫🇷 France | NVIDIA GB300 (13,800), GB200 (18K planned) | 🟡 44 MW (Q2 2026) | 200 MW EU by 2027; Sweden (EcoDataCenter) | EU sovereign AI alternative to US; trains own frontier LLMs; $830M debt raise (Bpifrance, BNP, HSBC); NVIDIA premier partner | |
| **Nebius Group** | 🇳🇱 Netherlands | H100, H200, GB300 | 🟢 170–220 MW | 2.5–3 GW; Finland 310MW, France 240MW | EU-hosted flagship in Finland; Microsoft + Meta contracts | ◆ |
| **OVHcloud** | 🇫🇷 France | H100, A100, L40S | 🟢 EU multi-region | Expanding | SecNumCloud; GDPR-native; EU's largest independent cloud; French public sector | |
| **Atos / Eviden** | 🇫🇷 France | BullSequana XH3000, NVIDIA + AMD | 🟢 National HPC sites | EuroHPC contracts | SecNumCloud; EUCS; builds sovereign supercomputers for EU govts; French defence | |
| **Northern Data / Taiga** | 🇩🇪 Germany | H100, A100 (~10K GPUs) | 🟢 ~30–50 MW | SE, NO, UK, PT sites | EU sovereign GPU cloud; crypto→AI pivot; Core42 JV 10K GPU access | |
| **Domyn** | 🇫🇷 France | NVIDIA Blackwell | 🟡 Building | 3,000 exaFLOPS EU program | NVIDIA EU sovereign push alongside Mistral + Nscale | |
| **STACKIT (Schwarz Group)** | 🇩🇪 Germany | GPU cloud | 🟢 EU sovereign regions | Expanding public sector | Lidl/Kaufland parent; GDPR-native; German public sector + retail enterprise | |
| **EuroHPC JU** | EU supranational | LUMI (AMD MI250X), Leonardo (A100), MareNostrum 5 | 🟢 8+ petascale nodes | Exascale expansion | EU-funded; governs sovereign HPC across member states; LUMI (Finland) = Europe's fastest | |
| **metalstack.cloud** ◆ | 🇩🇪 Germany | Bare metal Kubernetes | 🟢 Germany | Open-source K8s | Open-source managed K8s on bare metal; physical tenant isolation; GDPR | |
| **Genesis Cloud** ◆ | 🇩🇪 Germany | HGX H100, GB200 NVL72 | 🟢 EU multi-site | Expanding clusters | EU sovereign; GDPR; renewable energy; LLM training; enterprise compliance | |
| **Gcore** ◆ | 🇱🇺 Luxembourg | H100, A100, L40S | 🟢 180+ PoPs; 50+ locations | Expanding | EU sovereign + global edge; CDN-integrated; DDoS-resilient | |
| **Hyperstack / NexGen** ◆ | 🇬🇧 UK / 🇳🇴 Norway | H100 SXM, A100, L40S | 🟢 EU + North America | Expanding green cloud | Green cloud; NVLink enabled; EU data residency | |
| **DataCrunch / Verda** ◆ | 🇫🇮 Finland | H100, A100 | 🟢 Nordic sites | Renewable expansion | 100% renewable hydro + geothermal; EU sovereignty; GDPR | |

---

## Sovereign AI Clouds — Middle East

| Company | Nation | GPU / Compute | Scale | Pipeline | Key Notes |
|---|---|---|---|---|---|
| **G42 / Core42** | 🇦🇪 UAE | NVIDIA GB300, Cerebras | 🟡 Phase 1: 1 GW | 5 GW UAE-US AI Campus (Abu Dhabi); EU + Africa | UAE sovereign champion; Stargate UAE (OpenAI/Oracle/NVIDIA/SoftBank); Microsoft $15.2B; Falcon + K2-Think LLMs; 500K GPUs/yr from NVIDIA |
| **HUMAIN** | 🇸🇦 Saudi Arabia | NVIDIA Blackwell (18K), ~600K GPUs planned | 🟡 $100B mandate | 1.3 GW target by 2030 | PIF ($930B SWF); AWS $5B AI Zone; Google $10B; xAI first customer; ALLAM Arabic LLM; Groq $1.5B inference DC |
| **DAMAC Digital** | 🇦🇪 UAE (global) | AI-ready hyperscale | 🟢 10+ MW Riyadh | 300 MW+ by 2026; 1 GW+ in 10 countries; $20B / 2 GW US; $2.3B / 144 MW Jakarta | Formerly EDGNEX; 10 countries (UAE, KSA, Turkey, Thailand, Malaysia, Indonesia, Greece, Spain, Finland, Italy); acquired Hyperco (Finland) 2025; hybrid cooling innovation |
| **Qai (Qatar Investment Authority)** | 🇶🇦 Qatar | TBD | 🔵 Early stage | QIA ($524B SWF) backed | Qatar national AI vehicle; launched end 2025; domestic + international AI infra investment |
| **MGX / Mubadala** | 🇦🇪 UAE | Investor / LP | 🔵 $100B AI infra fund | AI Infrastructure Partnership (BlackRock, Microsoft, GIP, KIA) | UAE SWF AI infra fund; backs G42, Crusoe, global AI plays; Kuwait KIA joined 2025 |
| **TII (Abu Dhabi)** | 🇦🇪 UAE | NVIDIA, Cerebras | 🟢 Sovereign research | Falcon model expansion | UAE govt research lab; Falcon 40B/180B/Arabic/H1 LLMs; sovereign AI compute for Abu Dhabi |
| **NEOM / DataVolt** | 🇸🇦 Saudi Arabia | NVIDIA AI factory | 🟡 1.5 GW planned | $5B DataVolt deal | NEOM smart city project; sovereign Saudi digital infrastructure |

---

## Sovereign AI Clouds — Asia-Pacific & Other Regions

| Company | Nation | GPU / Compute | Scale | Sovereign Notes |  |
|---|---|---|---|---|---|
| **Ola Krutrim** ◆ | 🇮🇳 India | NVIDIA + own AI chip | 🟡 Building | India's first sovereign AI cloud; GPU-accelerated + domestic AI chip development; builds own LLMs | |
| **Tata Group AI Infra** | 🇮🇳 India | NVIDIA GH200 | 🟡 Building | India national AI infra; NVIDIA GH200-powered; National Data Center Policy | |
| **Reliance Industries / Jio** | 🇮🇳 India | NVIDIA | 🟡 Building | Sovereign foundation model for 20+ Indian languages; NVIDIA partnership | |
| **NeevCloud** ◆ | 🇮🇳 India | H100, A100 | 🟢 India | India-based GPU cloud; secure scalable AI compute; data residency compliance | |
| **E2E Cloud** ◆ | 🇮🇳 India | H100, A100 | 🟢 India | Indian GPU cloud; affordable AI/ML infra; IT Act compliance | |
| **FPT Vietnam** ◆ | 🇻🇳 Vietnam | NVIDIA (AI factory) | 🟡 $200M AI factory | Vietnam sovereign cloud; NVIDIA-powered AI factory; boosts Vietnam digital sovereignty | |
| **GMO GPU Cloud** ◆ | 🇯🇵 Japan | NVIDIA latest GPUs | 🟢 Japan | Japan sovereign GPU cloud; data residency + compliance; Japanese enterprise + govt | |
| **NTT Data (Oracle JV)** | 🇯🇵 Japan | Oracle OCI, NVIDIA | 🟢 Japan sovereign regions | Japan sovereign cloud; 150+ OCI services within Japanese jurisdiction | |
| **Singtel** | 🇸🇬 Singapore | NVIDIA H100, Hopper | 🟢 SE Asia AI factories | Singapore sovereign; upgraded NSCC with H100; building energy-efficient AI factories across SE Asia | |
| **DAMAC Digital — Indonesia** | 🇮🇩 Indonesia | AI-ready hyperscale | 🟡 144 MW / $2.3B | Largest single AI DC investment in Indonesia; local data residency mandate | |
| **Jottacloud** ◆ | 🇳🇴 Norway | Cloud storage | 🟢 Norway | Norwegian cloud storage under strict Norwegian privacy laws; US cloud alternative | |

---

## North America — Government / Classified Sovereign

| Company | Nation | GPU / Compute | Scale | Accreditation | Notes |
|---|---|---|---|---|---|
| **AWS GovCloud** | 🇺🇸 USA | Trainium, Inferentia, NVIDIA | 🟢 US East + West sovereign regions | FedRAMP High; DoD IL2–5; ITAR; CJIS | 30%+ US govt cloud share; air-gapped secret + TS; Saudi HUMAIN $5B AI Zone partner |
| **Microsoft Azure Government / Classified** | 🇺🇸 USA (global) | NVIDIA sovereign, Azure Maia | 🟢 15+ sovereign country regions | FedRAMP High; DoD IL5; Germany/UAE/Japan | Sovereign regions in 15+ countries; air-gapped classified; largest neocloud buyer $33B+ external GPU |
| **Oracle National Security Regions** | 🇺🇸 USA (global) | NVIDIA OCI, AI clusters | 🟢 Air-gapped regions | IL6 Top Secret; Japan + EU sovereign | Air-gapped classified cloud; expanding internationally; NTT Data JV in Japan |
| **IBM Cloud for Government** | 🇺🇸 USA | NVIDIA + IBM AI | 🟢 US federal + state | FedRAMP High; HIPAA; FISMA | ~7% US govt cloud share; hybrid cloud + watsonx AI; regulated industries specialist |

---

## Sources & Methodology

This list is compiled from:
- [Datum Cloud awesome-alt-clouds](https://github.com/datum-cloud/awesome-alt-clouds) GitHub list
- [Synergy Research Group](https://www.srgresearch.com/) neocloud market data
- [BloombergNEF](https://about.bnef.com/) AI data center capacity tracking
- [SemiAnalysis ClusterMAX 2.0](https://newsletter.semianalysis.com/) GPU cloud ratings
- [NVIDIA Newsroom](https://nvidianews.nvidia.com/) sovereign AI partnership announcements
- Company press releases, SEC filings, and investor presentations

**Last updated:** April 2026 | **Providers listed:** ~90 | **Maintained by:** [@8bitgangsta](https://github.com/8bitgangsta)

> 💡 **Contributing:** To suggest additions or corrections, open an issue or PR.
