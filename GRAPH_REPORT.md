# Graph Report - GravityDesk  (2026-10-18)

## Corpus Check
- 305 files · ~203,240 words
- Verdict: corpus is large enough that graph structure adds value.
- Unclassified: 20 file(s) not represented in the graph (top: .example 6, (none) 6, .cmd 2)

## Summary
- 2793 nodes · 5231 edges · 202 communities (115 shown, 87 thin omitted)
- Extraction: 96% EXTRACTED · 4% INFERRED · 0% AMBIGUOUS · INFERRED: 201 edges (avg confidence: 0.91)
- Token cost: 0 input · 0 output

## Community Hubs (Navigation)
- Bridge Swarm Scheduler
- Frontend Simulation Director
- CipherTool Cryptography Module
- Frontend Simulation Director
- Bridge Specialized Agents
- AI Lab Python Solutions
- AI Lab Python Solutions
- Three.js 3D Visuals & Rigs
- Antigravity Build Specification
- Antigravity Build Specification
- Context Masking Plugin
- Frontend API Client & Services
- Bridge Verification Pipeline
- Bridge Swarm Repository
- Three.js 3D Visuals & Rigs
- Frontend API Client & Services
- CRYPTracker Crypto Monitor
- Frontend API Client & Services
- Package Module
- Layout Module
- Frontend API Client & Services
- Nav Module
- Three.js 3D Visuals & Rigs
- Swarm Supervisor Module
- RogueCrawler Game Engine
- InMemoryCache Key-Value Store
- Three.js 3D Visuals & Rigs
- Architecture Technical Whitepaper
- Architecture Technical Whitepaper
- RogueCrawler Game Engine
- RogueCrawler Game Engine
- Test Gateway Module
- Swarm Privacy Module
- Phase Engine Module
- RogueCrawler Game Engine
- Frontend API Client & Services
- InMemoryCache Key-Value Store
- Readme Module
- Readme Module
- Frontend API Client & Services
- RogueCrawler Game Engine
- Test Gateway Module
- Scripts Module
- Config Module
- Realrunner Module
- Data Module
- Server Module
- Lane Module
- Lane Module
- Tsconfig Module
- Package Module
- InMemoryCache Key-Value Store
- RogueCrawler Game Engine
- Project Detailed Description
- Frontend Gateway Module
- Router Module
- Frontend Simulation Director
- AI Lab Python Solutions
- CRYPTracker Crypto Monitor
- InMemoryCache Key-Value Store
- Frontend Simulation Director
- Swarm Module
- Base Module
- Blackboard Module
- InMemoryCache Key-Value Store
- Triage And Planning Module
- CRYPTracker Crypto Monitor
- RogueCrawler Game Engine
- Router Module
- Planner Module
- Model Routing And Module
- Package Module
- Departments Module
- Base Module
- Base Module
- Base Module
- Frontend API Client & Services
- Readme Module
- Collect Module
- Clock Module
- Frontend API Client & Services
- Package Module
- Mockswarm Module
- Frontend Simulation Director
- Lane Module
- Realgravity Integration Module
- Fakes Module
- Fakes Module
- Pseudonymize Module
- Bridge Spec Module
- Projectbundle Module
- Redact Module
- 00 Start Here Module
- AI Lab Python Solutions
- Base Module
- Classify Module
- Readme Module
- Bridge Specialized Agents
- Evals Tasks Task Module
- Evals Tasks Task Module
- Evals Tasks Task Module
- Base Module
- Estimator Module
- Router Module
- Estimator Module
- Router Module
- Architecture Module
- Licenses Module
- Bridge Specialized Agents
- Base Module
- Departments Module
- Triage Module
- Clock Module
- Departments Module
- Triage Module
- Clock Module
- Clock Module
- Acceptance Tests Module
- Changes And Fixes Module
- RogueCrawler Game Engine
- Escape Tests Module
- Providers Module
- Breaker Module
- Providers Module
- Base Module
- Base Module
- Bridge Swarm Scheduler
- Topology Module
- Docker Compose Module
- Settings Module
- Lane Module
- Lane Module
- Test Gateway Module
- AI Lab Python Solutions
- CipherTool Cryptography Module
- CRYPTracker Crypto Monitor
- InMemoryCache Key-Value Store
- RogueCrawler Game Engine
- Models Module
- Swarm Module
- Models Module
- Run Module
- Check Module
- Check Module
- Check Module
- Check Module
- Gen Profiles Module
- Preflight Module
- Quota Module
- Setup Docker Storage Module
- Personas Module
- Readme Module
- Readme Module
- Test Gateway Module
- Test Gateway Module
- Vite Env.d Module
- Outputreadme Module
- Gravitydesk Banner Module
- Gravitydesk Header Module
- Allowlist Module
- Prompt Module
- Prompt Module
- Prompt Module
- Prompt Module
- Hosted Allowed Module
- Pyproject Module
- Pyproject Module
- Index Module
- Read Me First Module
- Gitignore Module
- Hosted Allowed Module
- CRYPTracker Crypto Monitor

## God Nodes (most connected - your core abstractions)
1. `useStore` - 58 edges
2. `director` - 57 edges
3. `SwarmRepository` - 44 edges
4. `SwarmController` - 36 edges
5. `CapacityMap` - 35 edges
6. `Cache` - 34 edges
7. `SwarmDirector` - 33 edges
8. `PhaseEngine` - 29 edges
9. `Entity` - 29 edges
10. `SwarmMessage` - 27 edges

## Surprising Connections (you probably didn't know these)
- `CircuitBreaker` --uses--> `Clock`  [INFERRED]
  bridge/deskmates_bridge/gateway/breaker.py → bridge/deskmates_bridge/gateway/clock.py
- `Gateway` --uses--> `CircuitBreaker`  [INFERRED]
  bridge/deskmates_bridge/gateway/router.py → bridge/deskmates_bridge/gateway/breaker.py
- `ProviderLane` --uses--> `Clock`  [INFERRED]
  bridge/deskmates_bridge/gateway/lane.py → bridge/deskmates_bridge/gateway/clock.py
- `Gateway` --uses--> `Clock`  [INFERRED]
  bridge/deskmates_bridge/gateway/router.py → bridge/deskmates_bridge/gateway/clock.py
- `Gateway` --uses--> `TokenEstimator`  [INFERRED]
  bridge/deskmates_bridge/gateway/router.py → bridge/deskmates_bridge/gateway/estimator.py

## Import Cycles
- None detected.

## Communities (202 total, 87 thin omitted)

### Community 0 - "Bridge Swarm Scheduler"
Cohesion: 0.07
Nodes (16): RoundEstimate, RunEstimator, SwarmRunEstimate, WaveDispatcher, AdmissionController, AdmissionResult, CapacityBucket, CapacityMap (+8 more)

### Community 1 - "Frontend Simulation Director"
Cohesion: 0.06
Nodes (26): Slot, ACCEL, CARRY_SPEED, TURN_RATE, WALK_SPEED, AgentDef, Pt, Act (+18 more)

### Community 2 - "CipherTool Cryptography Module"
Cohesion: 0.05
Nodes (24): caesar_brute_force(), caesar_decrypt(), caesar_encrypt(), _shift_char(), build_parser(), caesar_brute_force(), caesar_decrypt(), caesar_encrypt() (+16 more)

### Community 3 - "Frontend Simulation Director"
Cohesion: 0.07
Nodes (22): angleAtArc(), ArcTable, buildArcTable(), buildHallLayout(), CoffeeSlot, faceInward(), HALL_CONST, HallLayout (+14 more)

### Community 4 - "Bridge Specialized Agents"
Cohesion: 0.10
Nodes (14): BaseAgent, CoderAgent, CriticAgent, ArchivistAgent, IntegratorAgent, JudgeAgent, RedTeamAgent, ScoutAgent (+6 more)

### Community 5 - "AI Lab Python Solutions"
Cohesion: 0.08
Nodes (18): SwarmEventStream, CritiqueAssignmentSolver, LocalClusterer, SwarmClusterGroup, tokenize(), compute_distinctness(), PersonaSeatAllocator, SwarmSeat (+10 more)

### Community 6 - "AI Lab Python Solutions"
Cohesion: 0.06
Nodes (5): bfs(), compare_traversals(), dfs(), Queue, Stack

### Community 7 - "Three.js 3D Visuals & Rigs"
Cohesion: 0.09
Nodes (38): CHAIR_TYPES, chairParts(), laptopParts(), legSet(), monitorParts(), Part, partsFor(), plantParts() (+30 more)

### Community 8 - "Antigravity Build Specification"
Cohesion: 0.05
Nodes (42): 10. Edit Visibility (R9, R10), 11.1 Threat model, 11.2 Escape tests (`scripts/escape-tests.sh`), 11. Safety Verification, 12. Evaluation Harness (Phase 8), 13. Unknowns With Prescribed Resolution, 14. Operations, 15. Definition of Done (+34 more)

### Community 9 - "Antigravity Build Specification"
Cohesion: 0.05
Nodes (42): 10. Edit Visibility (R9, R10), 11.1 Threat model, 11.2 Escape tests (`scripts/escape-tests.sh`), 11. Safety Verification, 12. Evaluation Harness (Phase 8), 13. Unknowns With Prescribed Resolution, 14. Operations, 15. Definition of Done (+34 more)

### Community 10 - "Context Masking Plugin"
Cohesion: 0.09
Nodes (26): NEVER_MASK, setup(), applyReplacements(), errorTrim(), estTokens(), placeholder(), planMask(), sha8() (+18 more)

### Community 11 - "Frontend API Client & Services"
Cohesion: 0.07
Nodes (3): ApiClient, HttpClient, LiveEngine

### Community 12 - "Bridge Verification Pipeline"
Cohesion: 0.08
Nodes (10): BehavioralClusterer, CrossExamEngine, CrossExamMatrix, VerificationPipeline, VerificationResult, CandidateScores, SelectionScorer, test_crossexam_codet_dual_agreement_and_quarantine() (+2 more)

### Community 14 - "Three.js 3D Visuals & Rigs"
Cohesion: 0.11
Nodes (28): blobMat, buildRig(), HAIR_COLORS, mulberry(), Rig, RigPose, shared, SKIN_TONES (+20 more)

### Community 15 - "Frontend API Client & Services"
Cohesion: 0.09
Nodes (35): Agent, AgentSchema, ArtifactSchema, BlackboardNote, BlackboardNoteSchema, BreakPolicySchema, Config, ConfigSchema (+27 more)

### Community 16 - "CRYPTracker Crypto Monitor"
Cohesion: 0.06
Nodes (35): dependencies, lucide-react, react, react-dom, devDependencies, autoprefixer, postcss, tailwindcss (+27 more)

### Community 17 - "Frontend API Client & Services"
Cohesion: 0.09
Nodes (20): health_check(), approve_frame(), broadcast_event(), ConsentRequest, FrameApproveRequest, get_admission(), get_board(), get_egress_audit() (+12 more)

### Community 18 - "Package Module"
Cohesion: 0.06
Nodes (34): autoprefixer, postcss, react, react-dom, tailwindcss, @types/react, @types/react-dom, typescript (+26 more)

### Community 19 - "Layout Module"
Cohesion: 0.07
Nodes (29): addItem(), bay(), cabinTableSeats, chatPairs, content, data, Door, doors (+21 more)

### Community 20 - "Frontend API Client & Services"
Cohesion: 0.09
Nodes (31): DepartmentDef, parseEvent(), BLOCKED, Bay, BAY_ORDER, BreakPolicy, DAY_START_MIN, DEFAULT_ACCENT (+23 more)

### Community 21 - "Nav Module"
Cohesion: 0.15
Nodes (16): LAYOUT, AGENT_R, errs, astar(), cache, findPath(), Heap, primeCache() (+8 more)

### Community 22 - "Three.js 3D Visuals & Rigs"
Cohesion: 0.16
Nodes (25): STATUS_COLORS, deptColorRT(), hasDept(), useStore, cameraCtl, CamTarget, ComputeDrawer(), KV() (+17 more)

### Community 23 - "Swarm Supervisor Module"
Cohesion: 0.14
Nodes (7): SupervisorArbiter, SwarmDirective, WatchdogIncident, WatchdogManager, test_directive_validation(), test_supervisor_degraded_mode_fallback(), test_watchdogs_scope_and_stall()

### Community 24 - "RogueCrawler Game Engine"
Cohesion: 0.09
Nodes (7): Accessory, Armor, Inventory, Item, ItemType, StatusType, Weapon

### Community 26 - "Three.js 3D Visuals & Rigs"
Cohesion: 0.17
Nodes (21): USE_MOCK, App(), sfx, engine, GOLDEN_GOAL, resetAccentBlend(), setAccent(), I (+13 more)

### Community 27 - "Architecture Technical Whitepaper"
Cohesion: 0.07
Nodes (29): 10. Performance & Operational Benchmarks, 11. Conclusion, 1. Executive Summary, 2. Core Architectural Invariants, 3.1. Native Engine (Ultra-Lightweight Profile), 3.2. Docker Sandbox Engine (Hardened Isolation Profile), 3. Dual Execution Engine Architecture, 4.1. Supported Provider Matrix (100% Free Tiers) (+21 more)

### Community 28 - "Architecture Technical Whitepaper"
Cohesion: 0.07
Nodes (29): 10. Performance & Operational Benchmarks, 11. Conclusion, 1. Executive Summary, 2. Core Architectural Invariants, 3.1. Native Engine (Ultra-Lightweight Profile), 3.2. Docker Sandbox Engine (Hardened Isolation Profile), 3. Dual Execution Engine Architecture, 4.1. Supported Provider Matrix (100% Free Tiers) (+21 more)

### Community 29 - "RogueCrawler Game Engine"
Cohesion: 0.09
Nodes (10): _create_demo_game(), Interactable, Item, bfs_reachable(), deterministic_seed(), dungeon(), engine(), monsters() (+2 more)

### Community 30 - "RogueCrawler Game Engine"
Cohesion: 0.09
Nodes (3): Entity, Monster, Scheduler

### Community 31 - "Test Gateway Module"
Cohesion: 0.12
Nodes (15): _call_small_only(), make(), test_429_with_retry_after_is_absorbed_caller_sees_success(), test_429_without_header_backs_off_exponentially_and_halves_rate(), test_5xx_retries_same_model_twice_then_falls_back_to_next_model(), test_aging_prevents_starvation(), test_auth_failure_kills_the_provider_for_the_run_and_reports_it(), test_context_error_does_not_retry_and_advances_chain() (+7 more)

### Community 32 - "Swarm Privacy Module"
Cohesion: 0.15
Nodes (8): CanaryManager, CanaryLeakViolation, EgressFirewall, EgressFirewallViolation, ProviderTrust, TrustRegistry, test_canary_leak_protection(), test_trust_registry_strict_local()

### Community 33 - "Phase Engine Module"
Cohesion: 0.16
Nodes (5): PhaseEngine, SwarmBallot, VoteTallyEngine, test_borda_and_early_decision(), test_veto_blocks_cluster_selection()

### Community 35 - "Frontend API Client & Services"
Cohesion: 0.13
Nodes (5): create_task(), SwarmController, SwarmEvent, test_full_deliberative_flow_end_to_end(), test_benchmark_arms_execution()

### Community 37 - "Readme Module"
Cohesion: 0.08
Nodes (25): 1. Get your free API keys, 2. Configure, 3. Run preflight (first time only), 4. Launch, Available Models (all free), Change defaults, Egress Allowlist, Evaluation Harness (+17 more)

### Community 38 - "Readme Module"
Cohesion: 0.08
Nodes (25): 1. Get your free API keys, 2. Configure, 3. Run preflight (first time only), 4. Launch, Available Models (all free), Change defaults, Egress Allowlist, Evaluation Harness (+17 more)

### Community 39 - "Frontend API Client & Services"
Cohesion: 0.13
Nodes (8): Envelope, goldenRunEvents(), hhmm(), MockSimulator, fakeTick(), MockEngine, pushLogSafe(), tapeFor()

### Community 40 - "RogueCrawler Game Engine"
Cohesion: 0.14
Nodes (8): _carve_h_corridor(), _carve_room(), _carve_v_corridor(), _create_empty_map(), generate_dungeon(), place_player_at_entrance(), Rect, Tile

### Community 41 - "Test Gateway Module"
Cohesion: 0.14
Nodes (13): test_safety_factor_keeps_rate_below_configured_limit(), _call_small_only(), make(), test_429_with_retry_after_is_absorbed_caller_sees_success(), test_429_without_header_backs_off_exponentially_and_halves_rate(), test_5xx_retries_same_model_twice_then_falls_back_to_next_model(), test_auth_failure_kills_the_provider_for_the_run_and_reports_it(), test_context_error_does_not_retry_and_advances_chain() (+5 more)

### Community 42 - "Scripts Module"
Cohesion: 0.16
Nodes (6): main(), parse_env(), main(), main(), run_cmd(), extract_any()

### Community 43 - "Config Module"
Cohesion: 0.17
Nodes (16): AppSwarmConfig, BudgetsConfig, DiversityConfig, get_config_dir(), load_personas(), load_swarm_config(), MessagingConfig, PersonaCard (+8 more)

### Community 44 - "Realrunner Module"
Cohesion: 0.18
Nodes (15): EDIT_TOOLS, GOALS, executeTool(), parseAction(), runAutonomousAgent(), ToolCall, callLLM(), emitEvent() (+7 more)

### Community 45 - "Data Module"
Cohesion: 0.16
Nodes (18): buildOrg(), DAG_EDGES, DAG_NODES, deskOf(), leadChairFor(), llmBig, modelContext(), MODELS (+10 more)

### Community 46 - "Server Module"
Cohesion: 0.14
Nodes (15): config, createServer(), scan(), emit(), json(), readBody(), Run, runs (+7 more)

### Community 47 - "Lane Module"
Cohesion: 0.17
Nodes (3): Lease, ProviderLane, _Waiter

### Community 48 - "Lane Module"
Cohesion: 0.17
Nodes (3): Lease, ProviderLane, _Waiter

### Community 49 - "Tsconfig Module"
Cohesion: 0.10
Nodes (20): compilerOptions, allowImportingTsExtensions, baseUrl, isolatedModules, jsx, lib, module, moduleResolution (+12 more)

### Community 50 - "Package Module"
Cohesion: 0.10
Nodes (20): author, description, keywords, license, name, private, scripts, bridge:mock (+12 more)

### Community 51 - "InMemoryCache Key-Value Store"
Cohesion: 0.15
Nodes (3): KeyNotFoundError, core_cache(), lru_cache()

### Community 52 - "RogueCrawler Game Engine"
Cohesion: 0.13
Nodes (3): Consumable, Entity, GameEngine

### Community 53 - "Project Detailed Description"
Cohesion: 0.11
Nodes (18): 1.1 The One-Liner, 1.2 The Core Problem, 1.3 The GravityDesk Breakthrough, 1. Executive Overview (Non-Technical Pitch), 2.1 Three-Tier System Diagram, 2. Technical Architecture & System Anatomy, 3. The 6-Phase Swarm Consensus Lifecycle, 4. Key USPs (Unique Selling Propositions) (+10 more)

### Community 54 - "Frontend Gateway Module"
Cohesion: 0.14
Nodes (3): CircuitBreaker, Clock, Hub

### Community 55 - "Router Module"
Cohesion: 0.22
Nodes (6): LaneConfig, Gateway, ModelRouter, ModelSpec, Upstream, UpstreamResponse

### Community 56 - "Frontend Simulation Director"
Cohesion: 0.14
Nodes (7): EventStream, RT, ChatMessage, managerAgent, ManagerMemoryAgent, haltEntireSystem(), EventLog()

### Community 57 - "AI Lab Python Solutions"
Cohesion: 0.16
Nodes (8): element_frequencies(), max_min(), merge_unique(), remove_duplicates(), reverse_list(), second_largest(), sort_ascending(), sort_descending()

### Community 58 - "CRYPTracker Crypto Monitor"
Cohesion: 0.11
Nodes (17): compilerOptions, allowImportingTsExtensions, isolatedModules, jsx, lib, module, moduleResolution, noEmit (+9 more)

### Community 60 - "Frontend Simulation Director"
Cohesion: 0.21
Nodes (11): swarmDirector, cardPos(), cardTexture(), IdeaBoard(), voteFx, SwarmAgents(), CanvasBoundary, Lights() (+3 more)

### Community 61 - "Swarm Module"
Cohesion: 0.23
Nodes (14): CoffeeCorner(), HallProps(), ModeratorLectern(), ringShape(), SwarmChair(), textTexture(), V3, roleAt() (+6 more)

### Community 62 - "Base Module"
Cohesion: 0.14
Nodes (16): tools, models, openai/gpt-oss-120b, openai/gpt-oss-20b, qwen/qwen3.8-27b, capabilities, limit, modelID (+8 more)

### Community 63 - "Blackboard Module"
Cohesion: 0.18
Nodes (3): Blackboard, BlackboardEntry, DigestBuilder

### Community 65 - "Triage And Planning Module"
Cohesion: 0.12
Nodes (15): 1. Triage — what kind of task is this?, 2.1 Intensity → pacing (the "does it take breaks?" rule), 2.2 Budget pre-check (new, important), 2. Sizing — how complex is it? (the measurable part), 3. Org instantiation, 4. Plan — the manager decomposes (ONE structured LLM call), 5. Expand — leads decompose their branch (ONE short call per lead), 6.1 Worker kinds (what actually runs) (+7 more)

### Community 66 - "CRYPTracker Crypto Monitor"
Cohesion: 0.25
Nodes (9): App(), generateOrderBook(), getInitialAssets(), INITIAL_ASSETS, subscribeLivePrices(), CryptoAsset, OrderBookEntry, PriceAlert (+1 more)

### Community 68 - "Router Module"
Cohesion: 0.23
Nodes (6): LaneConfig, Gateway, ModelRouter, ModelSpec, Upstream, UpstreamResponse

### Community 69 - "Planner Module"
Cohesion: 0.19
Nodes (5): assert_path_in_scope(), in_scope(), PathGuardViolation, SwarmCell, TaskPlanner

### Community 70 - "Model Routing And Module"
Cohesion: 0.13
Nodes (14): 1. Architecture: the Gateway is an OpenAI-compatible local proxy, 2. Roles → models (all free / open-weight; verify ids on build day), 3. Context budgeting (prevents the other kind of error: 400 "context too long"), 4.1 Buckets, 4.2 Priority queue (what gets served first when there is not enough quota), 4.3 Error handling matrix, 4.4 Events the gateway emits (this *is* the "Compute & Cost" drawer's data), 4. The limiter, queue and resilience — precise behaviour (+6 more)

### Community 71 - "Package Module"
Cohesion: 0.13
Nodes (15): devDependencies, autoprefixer, postcss, tailwindcss, tsx, @types/node, @types/react, @types/react-dom (+7 more)

### Community 72 - "Departments Module"
Cohesion: 0.15
Nodes (9): bays, out, BAY_ZONES, colors, current, DeptRT, derive(), setDepartments() (+1 more)

### Community 73 - "Base Module"
Cohesion: 0.14
Nodes (13): autoupdate, compaction, auto, buffer, keep, default_agent, experimental, policies (+5 more)

### Community 74 - "Base Module"
Cohesion: 0.18
Nodes (14): capabilities, limit, modelID, name, limit, context, output, cohere/north-mini-code:free (+6 more)

### Community 75 - "Base Module"
Cohesion: 0.19
Nodes (14): settings, name, package, settings, settings, models, name, package (+6 more)

### Community 78 - "Readme Module"
Cohesion: 0.14
Nodes (13): 1. Deskmates Office Mode (Collaborative Sprint Execution), 1. Prerequisites, 2. Setup, 2. Swarm Hall Mode (Massive Consensus Synthesis), 3. Run GravityDesk, 🧪 Automated Test Suite, ⚡ Core Highlights, 🏛️ Dual Working Modalities (+5 more)

### Community 79 - "Collect Module"
Cohesion: 0.24
Nodes (5): get_nginx_stats(), get_sqlite_stats(), main(), parse_iso_timestamp(), main()

### Community 81 - "Frontend API Client & Services"
Cohesion: 0.15
Nodes (12): 1.1 What the frontend actually calls today, 1.2 REST, 1. Transport, 2. Event envelope, 3. WebSocket client → server messages, 4. Event types and payloads (all 36), 5. Behavioural rules the renderer relies on (the Bridge MUST honour these), Compute & permissions (+4 more)

### Community 82 - "Package Module"
Cohesion: 0.15
Nodes (13): dependencies, @dagrejs/dagre, framer-motion, jspdf, jszip, react, react-dom, @react-three/drei (+5 more)

### Community 83 - "Mockswarm Module"
Cohesion: 0.21
Nodes (12): RawEv, buildSwarmScript(), CHALLENGE, FRAME(), mulberry(), NAMES, PROPOSE, roleLabelOf() (+4 more)

### Community 84 - "Frontend Simulation Director"
Cohesion: 0.27
Nodes (10): applyEvent(), breakCaption(), defFromHire(), fmtEffort(), name(), pushLog(), rebuildSwarmDirector(), PHASES (+2 more)

### Community 86 - "Realgravity Integration Module"
Cohesion: 0.17
Nodes (11): 10. What not to do, 1. Mapping — RealGravity internals ↔ Deskmates concepts, 2. Step 0 — discovery (do this FIRST, 1-2 hours; it de-risks everything), 3. Per-worker workspace and git, 4. Launching a worker (recipe), 5. The one new plugin: `plugins/deskmates/index.ts`, 6. Signals the Bridge reads (and how it turns them into events), 7. Profiles (+3 more)

### Community 90 - "Bridge Spec Module"
Cohesion: 0.18
Nodes (10): 1. Stack & layout, 2. Run lifecycle (what the Bridge does for one `POST /api/tasks`), 3. Identity & desks, 4. Event derivation — every UI fact has a real source, 5. REST/WS implementation notes, 6. Persistence (SQLite, WAL), 7. Breaks, energy, chats — derived, never invented, 8. Security & privacy (invariants — do not weaken) (+2 more)

### Community 91 - "Projectbundle Module"
Cohesion: 0.42
Nodes (9): downloadMarkdownReport(), downloadProjectZip(), downloadSingleFile(), generateProjectFiles(), ProjectFile, inline(), Md(), ReportView() (+1 more)

### Community 92 - "Redact Module"
Cohesion: 0.27
Nodes (4): is_high_entropy_secret(), redact_text(), shannon_entropy(), test_redaction_secrets_and_pii()

### Community 93 - "00 Start Here Module"
Cohesion: 0.20
Nodes (9): A1. API keys (this answers "do we need more APIs to avoid the per-minute limit?" — yes, more *providers*), A2. Decisions / information to collect, ⚑ A. Open items for the OWNER — ask them these before/while you build, B. Verified state of what you received (re-run to confirm), C. Build plan (do in order; each phase ends with its acceptance test), D. Non-negotiable rules, E. If you get stuck, Frontend backlog (small, specified, not done) (+1 more)

### Community 94 - "AI Lab Python Solutions"
Cohesion: 0.27
Nodes (4): build_graph(), neighbors(), node_degrees(), node_exists()

### Community 95 - "Base Module"
Cohesion: 0.22
Nodes (9): nvidia/llama-3.1-nemotron-70b-instruct, capabilities, limit, modelID, name, models, name, package (+1 more)

### Community 97 - "Readme Module"
Cohesion: 0.22
Nodes (8): Against a (mock) backend over real HTTP/WebSocket, Deskmates, Documentation (read in this order), Layout of the repo, License, Name, Run it (mock mode — works today, no keys), What is in the office

### Community 98 - "Bridge Specialized Agents"
Cohesion: 0.25
Nodes (7): Context discipline, PAG agent rules, Planning, Reporting, Safety, Verification (definition of done), Working

### Community 100 - "Evals Tasks Task Module"
Cohesion: 0.39
Nodes (3): process_data(), add(), reverse_string()

### Community 101 - "Evals Tasks Task Module"
Cohesion: 0.36
Nodes (3): process_data(), add(), reverse_string()

### Community 102 - "Evals Tasks Task Module"
Cohesion: 0.39
Nodes (3): process_data(), add(), reverse_string()

### Community 103 - "Base Module"
Cohesion: 0.25
Nodes (8): capabilities, modelID, name, models, name, package, deepseek-v4-flash, go

### Community 105 - "Router Module"
Cohesion: 0.29
Nodes (3): AllModelsFailed, ContextTooLong, UpstreamError

### Community 107 - "Router Module"
Cohesion: 0.29
Nodes (3): AllModelsFailed, ContextTooLong, UpstreamError

### Community 108 - "Architecture Module"
Cohesion: 0.25
Nodes (7): 1. The idea in one picture, 2. Who does what (and why), 3. Mapping of the owner's ideas to the design, 4. Ports & processes (local only), 5. Data flow of one heavy run (worked example, placeholder limits), 6. Failure containment, Architecture — how the pieces fit

### Community 109 - "Licenses Module"
Cohesion: 0.25
Nodes (7): Assets, Licenses, Models, npm dependencies (all permissive), Python (bridge/), RealGravity reference files, This repository

### Community 110 - "Bridge Specialized Agents"
Cohesion: 0.25
Nodes (7): Context discipline, PAG agent rules, Planning, Reporting, Safety, Verification (definition of done), Working

### Community 111 - "Base Module"
Cohesion: 0.29
Nodes (7): agents, build, explore, plan, model, model, model

### Community 112 - "Departments Module"
Cohesion: 0.29
Nodes (7): backend Config, Departments Config, content Config, data Config, frontend Config, qa Config, research Config

### Community 113 - "Triage Module"
Cohesion: 0.29
Nodes (7): Triage Config, effort_s Config, overrides Config, pace Config, thresholds Config, weights Config, workers Config

### Community 115 - "Departments Module"
Cohesion: 0.29
Nodes (7): backend Config, Departments Config, content Config, data Config, frontend Config, qa Config, research Config

### Community 116 - "Triage Module"
Cohesion: 0.29
Nodes (7): Triage Config, effort_s Config, overrides Config, pace Config, thresholds Config, weights Config, workers Config

### Community 119 - "Acceptance Tests Module"
Cohesion: 0.29
Nodes (6): Acceptance tests, Definition of done, Gateway tests (G-series, `bridge/tests/gateway`), Integration (B-series, from the original plan), Safety (S-series, RealGravity's existing `scripts/escape-tests.sh` S1-S9 must still pass untouched), Triage-layer tests (T-series)

### Community 120 - "Changes And Fixes Module"
Cohesion: 0.29
Nodes (6): A. The delivery would not have started, B. Wrong behaviour (found by the new end-to-end tests), C. Integration of the Triage Layer (GLM's change-set, applied with the fixes above), D. Additions that did not exist, E. Honest limits — read this, What was changed relative to GLM's delivery — and why

### Community 122 - "Escape Tests Module"
Cohesion: 0.40
Nodes (5): PAG_CTX_TIER, PROFILE, run_in_agent(), escape-tests.sh script, WORKSPACE

### Community 123 - "Providers Module"
Cohesion: 0.33
Nodes (6): Providers Config, global Config, go Config, groq Config, nvidia Config, openrouter Config

### Community 125 - "Providers Module"
Cohesion: 0.33
Nodes (6): Providers Config, global Config, go Config, groq Config, nvidia Config, openrouter Config

### Community 126 - "Base Module"
Cohesion: 0.40
Nodes (5): capabilities, limit, modelID, name, google/gemma-4-31b-it:free

### Community 127 - "Base Module"
Cohesion: 0.40
Nodes (5): qwen/qwen3.8-27b:free, capabilities, limit, modelID, name

### Community 134 - "Docker Compose Module"
Cohesion: 0.50
Nodes (4): Docker-compose Config, networks Config, services Config, volumes Config

### Community 135 - "Settings Module"
Cohesion: 0.50
Nodes (4): Settings Config, search Config, server Config, use_default_settings Config

### Community 139 - "AI Lab Python Solutions"
Cohesion: 0.50
Nodes (3): AI_Lab1PythonSolutions - Execution Deliverables, Generated Source Files:, Verification Status:

### Community 140 - "CipherTool Cryptography Module"
Cohesion: 0.50
Nodes (3): CipherTool - Execution Deliverables, Generated Source Files:, Verification Status:

### Community 141 - "CRYPTracker Crypto Monitor"
Cohesion: 0.50
Nodes (3): CRYPTracker - Real-Time Crypto Price Tracker, Features, Getting Started

### Community 142 - "InMemoryCache Key-Value Store"
Cohesion: 0.50
Nodes (3): Generated Source Files:, InMemoryCache - Execution Deliverables, Verification Status:

### Community 143 - "RogueCrawler Game Engine"
Cohesion: 0.50
Nodes (3): Generated Source Files:, RogueCrawler - Execution Deliverables, Verification Status:

### Community 148 - "Models Module"
Cohesion: 0.67
Nodes (3): aliases Config, Models Config, models Config

### Community 149 - "Swarm Module"
Cohesion: 0.67
Nodes (3): Swarm Config, privacy Config, swarm Config

### Community 150 - "Models Module"
Cohesion: 0.67
Nodes (3): aliases Config, Models Config, models Config

## Knowledge Gaps
- **385 isolated node(s):** `WORKSPACE`, `PROFILE`, `PAG_CTX_TIER`, `deskmates-bridge`, `deskmates-bridge` (+380 more)
  These have ≤1 connection - possible missing edges or undocumented components. (Counts symbols only; 1312 node(s) total have ≤1 connection when file, concept and rationale nodes are included.)
- **87 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `SwarmRepository` connect `Bridge Swarm Repository` to `Bridge Swarm Scheduler`, `Phase Engine Module`, `Frontend API Client & Services`, `AI Lab Python Solutions`, `Frontend API Client & Services`?**
  _High betweenness centrality (0.016) - this node is a cross-community bridge._
- **Are the 4 inferred relationships involving `SwarmRepository` (e.g. with `SwarmController` and `PhaseEngine`) actually correct?**
  _`SwarmRepository` has 4 INFERRED edges - model-reasoned connections that need verification._
- **What connects `WORKSPACE`, `PROFILE`, `PAG_CTX_TIER` to the rest of the system?**
  _385 weakly-connected nodes found - possible documentation gaps or missing edges._
- **Should `Bridge Swarm Scheduler` be split into smaller, more focused modules?**
  _Cohesion score 0.07042253521126761 - nodes in this community are weakly interconnected._
- **Why does `ProviderLane` connect `Lane Module` to `Clock Module`, `Frontend Gateway Module`, `Router Module`?**
  _High betweenness centrality (0.015) - this node is a cross-community bridge._
- **Are the 23 inferred relationships involving `SwarmController` (e.g. with `create_task()` and `Blackboard`) actually correct?**
  _`SwarmController` has 23 INFERRED edges - model-reasoned connections that need verification._
- **Should `Frontend Simulation Director` be split into smaller, more focused modules?**
  _Cohesion score 0.05926251097453907 - nodes in this community are weakly interconnected._