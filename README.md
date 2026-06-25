QUANTUM PRO: NEURAL INTERFACE (v12.5.0)QUANTUM PRO is an advanced, web-based Augmented Reality (AR) Heads-Up Display (HUD) and biometric neural interface. Collaborating cutting-edge computer vision with interactive audio-visual systems, the platform delivers real-time facial mesh tracking, precise eye-state analytics, and an integrated voice-controlled AI assistant ("Quanto AI").Designed with modular architecture, this repository is fully optimized for scalable web deployment and lightweight local execution.


⚡ Core FeaturesReal-Time Biometric Tracking: Utilizing Google MediaPipe Face Mesh for high-fidelity 3D facial landmark recognition.High-Resolution Eye Failsafe Protocol: Implements a strict, sub-millisecond precision tracking mechanism using performance.now() to detect dual eye-closure. Triggers an audio-visual warning exactly at the 1.0-second threshold with instant wink-immunity resetting.Modular 3D Spatial Rendering: Leverages Three.js for dynamic, real-time rendering of complex topological wireframes mapping directly onto user movements with adaptive scaling.

Quanto AI Dynamic Voice Core: Features a native Web Speech API integration supporting hands-free voice commands, asynchronous speech queue chunking, live external API data streaming (Weather/Wikipedia), and context retention loops ("Start" / "Stop").Multi-Environmental Sub-Systems: Toggle seamless HUD operational modes including Standard, Stealth (visual/audio masking), and Quantum MK-X interfaces.


📂 Repository StructureThe project has been refactored into a clean, modular structure according to standard modern web development practices:Plaintext├── 

index.html      # Application entry point & DOM layout structure
├── style.css       # Core design tokens, global glassmorphic HUD styling, & animations
├── app.js          # Main engineering script (MediaPipe, Three.js, Web Audio, & Speech Core)
└── README.md       # Repository documentation


🚀 Getting StartedPrerequisitesTo run this application locally or host it on web servers, you require:A modern web browser supporting WebGL, Web Audio API, and Web Speech API (Google Chrome, Microsoft Edge, or Safari recommended).A functional webcam and microphone connected to your system.HTTPS Protocol: Secure origin execution is strictly required by modern browsers to grant webcam, microphone, and speech synthesis permissions.Local DeploymentTo run and test the interface on your local machine:Clone this repository to your environment:Bashgit clone https://github.com/Sushruta-byte/QUANTUM-PRO-NEURAL-INTERFACE.git


Navigate into the repository directory:Bashcd QUANTUM-PRO-NEURAL-INTERFACE
Launch a secure local development server. If you have Python installed, execute:Bash# Python 3.x
python -m http.server 8000


Open your web browser and navigate to: http://localhost:8000🛠️ Architecture & Technologies UsedFrontend Engine: Tailwind CSS — High-performance utility-first styling for glassmorphic layouts.Computer Vision Framework: Google MediaPipe Face Mesh — Client-side ML pipeline for multi-landmark tracking.Graphics Pipeline: Three.js (r128) — Hardware-accelerated 3D WebGL renderer handling procedural matrix scaling and positional vector interpolation (.lerp).Audio Synthesis: Native Web Audio API — Real-time programmatic generation of localized sawtooth warning oscillators independent of standard asset streaming bottlenecks.


🗣️ Voice Commands (Quantum MK-X Mode)When initializing the Quantum MK-X protocol, the following verbal triggers become accessible to interact with the Quanto AI Core:Command TriggerSystem Action / Response"Time"Vocalizes localized real-time data metrics."Weather"Dynamically pulls and reports current atmospheric and sensor analysis."Stop"Halts AI speech stream instantly while caching pending data segments."Start"Resumes the cached data stream seamlessly from the exact pause point.

📝 LicenseDistributed under the MIT License.

See LICENSE for more information.
