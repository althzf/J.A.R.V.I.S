# J.A.R.V.I.S
J.A.R.V.I.S. is a voice-controlled, offline-resilient personal desktop assistant built exclusively for Windows 10 and 11 (64-bit). Rather than acting as a simple AI chat wrapper, this project operates as an asynchronous, Bring-Your-Own-Key (BYOK) operating system automation suite.

Designed with a strict focus on privacy, it ensures that all conversation logs, cached audio, and generated artifacts remain exclusively on your local hard drive with zero telemetry or background tracking.

Core Capabilities
Multithreaded Architecture: Built with a dual-thread design that separates the continuous microphone logic loop from the 60fps graphical rendering engine.

Conversational AI & Live Search: Leverages Groq's high-speed inference models for natural dialogue while actively fetching live web data to bypass traditional AI knowledge cutoffs.

Complete OS Automation: Autonomously launches desktop applications, manages running processes, targets and closes specific browser tabs, and controls native Windows power states.

Artifact Synthesis: Programmatically drafts, formats, and launches fully structured Microsoft Word documents and PowerPoint presentations based on verbal commands.

Interactive Sci-Fi HUD: Rejects standard web UI in favor of a native PyQt5 interface featuring a rotating neural core, a draggable glassmorphism music visualizer, and live system hardware vitals.

Advanced Auditory Systems: Supports seamless voice interruption, premium voice cloning, and pre-cached offline audio to verbally diagnose the system if internet connectivity drops.
