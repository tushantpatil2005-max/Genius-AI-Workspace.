# Genius-AI-Workspace.

An elite, high-fidelity AI-powered productivity workspace offering deep reasoning, strategic brainstorming, creative copywriting, automated code synthesis, and cinematic prompt direction using advanced Gemini models.
This application utilizes a full-stack architecture (React client + Express/Node.js server) to securely proxy API calls, keeping secret keys hidden from the browser.
 Project Key Highlights
Dynamic Workspaces: Tailor intelligence behaviors across multiple specialized agent personas:
🔸 Genius Ideator: Tactical blue-ocean strategist & startup architect.
🔹 Deep Thinker: Formal systems logical theorist, auditor, and requirements analyzer.
🔻 Creative Scribe: Conversational storyteller & high-conversion rhetorician.
🔸 Synthesizer Mono: Ultra-precise code generator, component compiler, and debugger.
🔹 Visual Muse: Cinematic prompt recipe director, color theologian, and composition strategist.
Cognitive Trace Traceback: Read the granular, structured step-by-step reasoning tree explaining exactly how the AI structured its logic before arriving at the solution.
Dynamic Synthesized Artifacts: Outcomes are paired with functional interactives:
Checklists: Toggle items interactively to keep track of operational steps.
Dynamic Charts: Generate beautiful visual metrics or hypothetical multi-year growth bar charts.
Code Views: View pristine TypeScript, Node.js, and CSS files with a dedicated code previewer and instant copy-to-clipboard functionality.
🛠️ Tech Architecture
Frontend: React 19, TypeScript, Tailwind CSS, Lucide Icons, custom lightweight Markdown parser.
Backend (Secure Proxy): Express, TSX, esbuild, and the modern official @google/genai SDK.
Compilation Tooling: Seamlessly bundled under a single executable dist/server.cjs via esbuild for maximum container boot speeds in production.
 Installation & Local Execution
To start the Genius AI Workspace locally:
1. Configure Secrets & Environment
Create a .env file at your project root:
code
Env
GEMINI_API_KEY="your_gemini_api_key_here"
(In Google AI Studio, this key is managed securely via the Secrets panel under the Settings/Environment tab).
2. Install Workspace Dependencies
code
Bash
npm install
3. Start Development Engine
code
Bash
npm run dev
The developer server will boot on port 3000 at http://localhost:3000.
4. Build & Compile for Production Deployment
code
Bash
npm run build
npm start
This builds the client assets inside dist/ and compiles the Express backend server into a production-ready standalone bundle at dist/server.cjs.
lightbulb_tips
Make changes, add new features, ask for anything
