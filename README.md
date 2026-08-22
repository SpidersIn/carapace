🕷️ carapace by spidersIn
carapace is an advanced, distributed intelligence-gathering framework. Like a spider on its web, it detects vibrations in the target's infrastructure, silently collecting exposed data, subdomains, and hidden endpoints to weave a comprehensive attack surface map.

🕸️ Capabilities
Deep Crawling: Multi-threaded spidering engine that bypasses modern anti-bot protections.

Venom Modules: Optional active-probing modules to test for low-hanging vulnerabilities (e.g., exposed .git, .env).

Graph Silk: Automatically structures gathered intelligence into Neo4j graph databases for visual correlation.

Cross-Platform: Native execution without heavy virtualization.

🚀 Quick Start
Prerequisites
Python 3.10+

Fully tested and supported on both Windows 11 and Kali Linux.

Neo4j (Optional, for graph visualization).

Installation
Bash
# Clone the web
git clone https://github.com/spidersIn/carapace.git

# Navigate to directory
cd carapace

# Install dependencies (Windows/Kali compatible)
pip install -r requirements.txt

⚠️ Disclaimer
Built for defense, intelligence, and authorized red-teaming. Arachnid Sec is not responsible for individuals who use this tool to cast webs on unauthorized targets. Hack responsibly.
