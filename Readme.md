# Description

Generates commit message via local ollama installation.
Uses `tavernari/git-commit-message` as model.

- ✅ Works completely offline ‼️
- ✅ Does not send any company data into the cloud ☁
- ✅ Lightweight installation 🕊️
- ✅ Was developed on mac 💻

# Installation 
- install ollama from https://ollama.com
- make sure ollama runs by `ollama serve`
- install python packages
`pip install langchain_community` 
`pip install gitpython`
- copy `prepare-commit-msg` into `/path/to/.git/hooks`