IBA Public School Sukkur — Computer Science Interactive Presentation Platform

An interactive, responsive, single-file instructional web application designed for teaching Chapter 01: Computer Networks & Cloud Computing in Senior Secondary Computer Science courses.

🏛️ Institutional & Course Information

Institution: IBA Public School, Sukkur (Sindh, Pakistan)

Department: Department of Computer Science

Instructor / Curriculum Lead: Sir Abdul Razak

Subject: Computer Science — Chapter 01: Computer Networks & Cloud Computing

Curriculum Topics Covered:

1.5.3: Network Topologies (Bus, Ring, Star, Tree, Mesh, Hybrid) — Real-Life Analogies, Trade-offs & Practical Applications

1.5.4: Scalability vs. Reliability Engineering Testing (Load/Stress Testing, Benchmarking vs. Fault Tolerance, Redundancy, Disaster Recovery)

1.6.1: Cloud Computing Fundamentals & NIST Essential Characteristics (CapEx vs. OpEx)

1.6.2: Cloud Service Models (IaaS, PaaS, SaaS) with Interactive Analogies (Pizza-as-a-Service & Transport Modes)

1.6.3: Cloud Deployment Models (Public, Private, Community, Hybrid)

Assessment: Formative Module Review & Live Self-Scoring Assessment

✨ Key Features & Interactive Capabilities

1. 🖥️ Interactive Network Topology Sandbox

Dynamic SVG Simulation Engine: Interactive canvas supporting 6 topology modes:

Bus Topology: Interactive central coaxial cable severance simulation & 50Ω terminators.

Ring Topology: Unidirectional token loop with node break detection.

Star Topology: Central hub/switch outage simulation vs. isolated leaf failures.

Tree Topology: Hierarchical root core failure and sub-tree isolation dynamics.

Mesh Topology: Complete point-to-point mesh link matrix ($N(N-1)/2$) showing redundant fault tolerance.

Hybrid Topology: Multi-building Star-Bus campus network visualization (Lab A & Lab B).

Fault Injection: Click any workstation node (PC1–PC5) or central backbone/hub to observe instantaneous packet flow disruptions and status badge updates.

1. 📊 Scalability vs. Reliability Testing Dashboard

Side-by-side comparative analysis of engineering benchmarks:

Scalability Pillar: Load testing (60 req/s), stress testing, +50 workstation expansion verification, and IEEE 802.3 baselines.

Reliability Pillar: 99.9% Uptime SLA, dual fiber uplinks, disaster recovery snapshot restoration, and continuous SNMP/Syslog telemetry.

Live Campus Network Load Simulator: Interactive slider (10 to 600 concurrent student devices) calculating real-time:

Round-Trip Time (RTT in ms)

Packet Delivery Ratio (PDR %)

Network Jitter (ms)

Calculated Campus Uptime / SLA Rating

1. 🍕 Cloud Service Models & Analogy Switcher

Deep dive into IaaS, PaaS, and SaaS shared responsibility matrices.

Interactive Analogy Engine: Toggle between:

Pizza As A Service: Bake at Home (IaaS) $\rightarrow$ Pizza Delivery (PaaS) $\rightarrow$ Dine-in Restaurant (SaaS).

Transport Modes: Car Lease (IaaS) $\rightarrow$ Taxi / Careem Ride (PaaS) $\rightarrow$ Commercial Flight (SaaS).

1. 🌐 Cloud Deployment Architectures

Comparative multi-tenancy and data governance cards:

Public Cloud: Multi-tenant commercial clouds (AWS EC2, Microsoft Azure).

Private Cloud: Dedicated organizational infrastructure (Banking / Defense).

Community Cloud: Regional academic resource pooling (e.g., Sindh Universities Research Cloud).

Hybrid Cloud: Integrated on-campus private records + public admissions portal.

1. 🎯 Formative Assessment & Quiz Module

4 comprehensive multiple-choice questions testing syllabus mastery.

Instant visual validation (correct/incorrect states) with dynamic explanation callouts.

Live score calculation and one-click quiz reset functionality.

1. 🧑‍🏫 Smartboard / Lecture Presentation Mode

Dedicated Smartboard Mode toggle designed for interactive classroom flat-panels and overhead projectors:

Expands canvas to 100% viewport width.

Eliminates secondary margin clutter for enhanced readability from the back of the classroom.

1. 🌀 Dynamic Animated Browser Favicon

An inline HTML5 Canvas favicon rendering engine operating at 25 FPS that draws a glowing network hub and an actively orbiting data packet directly in the browser's tab icon.

🛠️ Technology Stack & Architecture

Architecture: Zero-dependency, single-file standalone web application (presentation.html).

Markup: Semantic HTML5 (<header>, <main>, <section>, <footer>, <svg>).

Styling: Tailwind CSS (via official CDN) utilizing custom corporate brand tokens (#0284C7, #38BDF8, #F0F9FF, #0F172A).

Typography: Google Fonts (Inter & JetBrains Mono).

Icons: Lucide Icons CDN + inline resolution-independent SVG illustrations.

Logic: Vanilla JavaScript (ES6+) with zero build tools, bundlers, or package dependencies required.

🚀 Getting Started & Execution

Option A: Local Browser Run (Direct)

Download or save the code file as presentation.html.

Double-click presentation.html or open it in any modern browser (Google Chrome, Microsoft Edge, Mozilla Firefox, Safari, Brave).

No local web server (npm, python -m http.server, etc.) is required; it runs immediately offline (CDN assets cache on first load).

Option B: Classroom Deployment / Static Web Hosting

You can deploy this single-file presentation to any static hosting provider in seconds:

GitHub Pages: Commit presentation.html as index.html in your repository root.

Vercel / Netlify / Cloudflare Pages: Drag-and-drop the directory containing the HTML file.

⌨️ Keyboard & Navigation Shortcuts

Action

Description

Top Nav Anchors

Smooth-scrolls directly to specific sub-topic sections.

Search Bar (Ctrl + F / Input)

Filters visible cards and sections by keyword in real time.

Smartboard Button

Toggles wide-screen classroom display margins.

Node Clicks

Click on any circular PC node in the topology canvas to trigger simulated hardware failure.

Backbone Click (Bus/Tree/Star)

Click on the central cable or switch to simulate core network collapse.

📄 License & Attribution

Curriculum Author: Sir Abdul Razak

Institution: IBA Public School, Sukkur

License: Educational Open Access — free for academic demonstration, classroom lecture use, and student revision.
