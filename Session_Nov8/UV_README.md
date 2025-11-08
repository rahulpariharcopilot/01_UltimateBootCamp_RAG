# 01_UltimateBootCamp_RAG --> UV Learning
**Please be ready with these before Next Saturday 15th Nov’25 class**

https://docs.astral.sh/uv/#installation
uv init example
cd example
uv add ruff
uv run ruff check
uv lock
uv sync

echo 'import requests; print(requests.get("https://astral.sh"))' > example.py

uv add --script example.py requests
uv run example.py

uvx pycowsay 'hello world!'

uv tool install ruff
ruff --version

uv python install 3.10 3.11 3.12
uv pip compile docs/requirements.in \
   --universal \
   --output-file docs/requirements.txt

uv venv --python 3.11

uv pip sync docs/requirements.txt

