# Python_Apps_Scripts


Quick GitHub setup for any of these
----------------------------------------------------------
mkdir <repo-name> && cd <repo-name>
python -m venv .venv && source .venv/bin/activate
pip install <deps>
# add the Python file(s)
echo -e ".venv/\n__pycache__/\n*.pyc\n.env" > .gitignore
# write a solid README.md
git init && git add . && git commit -m "Initial POC"

------------------------------------------------------------

These five are a strong mix of:
Platform / Image Builder tooling
Secure instance launching
Internal dashboards
ML serving
Governance / tagging
