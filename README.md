<h1 align="left">Raiymbek Zhaksilikov</h1>

<p align="left">
Backend engineer building distributed systems, AI infrastructure, and robotics platforms.<br/>
I design and ship production software where latency, correctness, and operational reliability are treated as hard constraints.
</p>

<hr/>

<h3 align="left">Areas of Expertise</h3>

<ul>
  <li>Backend architecture: asynchronous Python, API design, service decomposition</li>
  <li>AI systems: LLM orchestration, speech pipelines with Whisper, retrieval and agentic workflows</li>
  <li>Robotics and embedded: Raspberry Pi, ESP32, real-time control loops, sensor integration</li>
  <li>Streaming and networking: WebRTC, WebSockets, low-latency media transport</li>
  <li>Computer vision: OpenCV pipelines for perception and closed-loop control</li>
  <li>Data layer: PostgreSQL, Redis, schema design, transactional integrity</li>
  <li>Infrastructure: Linux, Docker, observability, reproducible deployments</li>
</ul>

<hr/>

<h3 align="left">Selected Projects</h3>

<p align="left"><b>Unmanned Ground Vehicle — Control and Perception System</b></p>
<p align="left">
End-to-end robotic platform integrating Raspberry Pi and ESP32 over a deterministic control channel. WebRTC transport delivers sub-second telemetry and video, while an OpenCV perception layer feeds a command pipeline engineered for bounded latency under unstable network conditions. Hardware, transport, and application layers are isolated as independently testable subsystems.
</p>

<br/>

<p align="left"><b>AI Voice and Text Assistant</b></p>
<p align="left">
Conversational system built on an asynchronous Python core, combining Whisper-based speech recognition with LLM reasoning. Architecture separates transport, domain logic, and model orchestration, enabling horizontal scaling of inference workloads and clean substitution of underlying models. Designed for high message throughput with predictable failure modes and strict timeout semantics.
</p>

<br/>

<p align="left"><b>Fuel Management Backend</b></p>
<p align="left">
Operational backend for vehicle refueling workflows. Normalized domain model, auditable transaction logs, structured reporting, and integrations with external provider APIs. Built around strong invariants, explicit state transitions, and a data layer optimized for reconciliation and long-term analytical queries.
</p>

<hr/>

<h3 align="left">Engineering Principles</h3>

<ul>
  <li>Systems are designed around explicit boundaries, contracts, and failure modes — not around frameworks.</li>
  <li>Correctness and observability precede optimization. What cannot be measured cannot be trusted.</li>
  <li>Asynchronous code is a tool, not a default. Concurrency models are chosen to match the workload.</li>
  <li>Simplicity is a requirement. Every abstraction must justify its cost in maintenance and cognitive load.</li>
  <li>Ownership spans the full lifecycle: design, implementation, deployment, and long-term operation.</li>
</ul>

<hr/>

<h3 align="left">Current Focus</h3>

<ul>
  <li>Production-grade LLM system design: context management, tool use, and evaluation pipelines</li>
  <li>Distributed asynchronous backends and resilient message-driven architectures</li>
  <li>Retrieval-augmented systems operating under strict latency and accuracy budgets</li>
</ul>
