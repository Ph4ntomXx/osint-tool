# 🕵️ OSINT Tool

**OSINT Tool** is a modular framework for open-source intelligence gathering.  
It allows you to search and collect information from public sources using:

- Names / Nicknames
- Emails
- Phone numbers
- Domains
- Images
- Usernames

Whether you're conducting investigations, verifying identities, or doing ethical hacking — this tool provides a solid foundation for building your own OSINT workflows.

---

## ✨ Key Features

- 🔍 Custom modules for email, phone, username, image & domain search
- 🧩 Integration with popular external tools (Sherlock, Holehe, PhoneInfoga, etc.)
- 🌐 API support: Shodan, Hunter.io, HaveIBeenPwned
- 💾 Save all results as JSON reports
- 📦 Expandable and fully modular structure
- ⌨️ Command-line interface (GUI coming soon)

---

## 📂 Project Structure

- `main.py` — Entry point of the tool (runs the CLI menu)
- `core/` — Custom modules for OSINT tasks (email, phone, etc.)
- `tools/` — External tools integrated locally (Sherlock, Holehe, etc.)
- `api/` — Scripts using APIs like Shodan, Hunter.io
- `config/` — JSON files for API keys and settings
- `data/` — All collected reports, screenshots and temporary files
- `utils/` — Helper scripts for logging, formatting and validation
- `tests/` — Unit tests for your modules

---

## 🚀 Getting Started

```bash
# Clone the repository
git clone https://github.com/yourusername/osint-tool.git
cd osint-tool

# Install dependencies
pip install -r requirements.txt

# Run the tool
python main.py
