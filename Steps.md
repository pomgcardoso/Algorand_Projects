# algorand-python-workshop

Welcome to your new AlgoKit project!

This is your workspace root. A `workspace` in AlgoKit is an orchestrated collection of standalone projects (backends, smart contracts, frontend apps and etc).

By default, `projects_root_path` parameter is set to `projects`. Which instructs AlgoKit CLI to create a new directory under `projects` directory when new project is instantiated via `algokit init` at the root of the workspace.

## Getting Started

To get started refer to `README.md` files in respective sub-projects in the `projects` directory.

To learn more about algokit, visit [documentation](https://github.com/algorandfoundation/algokit-cli/blob/main/docs/algokit.md).

### GitHub Codespaces

To get started execute:

1. `algokit generate devcontainer` - invoking this command from the root of this repository will create a `devcontainer.json` file with all the configuration needed to run this project in a GitHub codespace. [Run the repository inside a codespace](https://docs.github.com/en/codespaces/getting-started/quickstart) to get started.
2. `algokit init` - invoke this command inside a github codespace to launch an interactive wizard to guide you through the process of creating a new AlgoKit project

Powered by [Copier templates](https://copier.readthedocs.io/en/stable/).


TERMINAL


pedrocardoso@Pedros-Air algorand-python-workshop % algokit project bootstrap all
You are using AlgoKit version 2.6.2, however version 2.7.0 is available. Please update using `brew upgrade algokit`.
Installing Python dependencies and setting up Python virtual environment via Poetry
poetry: Creating virtualenv algorand-python-workshop in /Users/pedrocardoso/Projects/Algorand/workshop/algorand-python-workshop/projects/algorand-python-workshop/.venv
poetry: Installing dependencies from lock file
poetry: 
poetry: Package operations: 78 installs, 0 updates, 0 removals
poetry: 
poetry: - Installing idna (3.10)
poetry: - Installing pycparser (2.22)
poetry: - Installing sniffio (1.3.1)
poetry: - Installing h11 (0.14.0)
poetry: - Installing certifi (2025.1.31)
poetry: - Installing cffi (1.17.1)
poetry: - Installing anyio (4.9.0)
poetry: - Installing httpcore (0.16.3)
poetry: - Installing defusedxml (0.7.1)
poetry: - Installing frozenlist (1.5.0)
poetry: - Installing charset-normalizer (3.4.1)
poetry: - Installing msgpack (1.1.0)
poetry: - Installing multidict (6.4.3)
poetry: - Installing boolean-py (5.0)
poetry: - Installing mdurl (0.1.2)
poetry: - Installing propcache (0.3.1)
poetry: - Installing pynacl (1.5.0)
poetry: - Installing pycryptodomex (3.22.0)
poetry: - Installing rfc3986 (1.5.0)
poetry: - Installing urllib3 (2.4.0)
poetry: - Installing aiohappyeyeballs (2.6.1)
poetry: - Installing aiosignal (1.3.2)
poetry: - Installing distlib (0.3.9)
poetry: - Installing filelock (3.18.0)
poetry: - Installing license-expression (30.4.1)
poetry: - Installing packageurl-python (0.16.0)
poetry: - Installing packaging (24.2)
poetry: - Installing attrs (25.3.0)
poetry: - Installing markdown-it-py (3.0.0)
poetry: - Installing httpx (0.23.3)
poetry: - Installing platformdirs (4.3.7)
poetry: - Installing iniconfig (2.1.0)
poetry: - Installing pluggy (1.5.0)
poetry: - Installing py-algorand-sdk (2.8.0)
poetry: - Installing py-serializable (2.0.0)
poetry: - Installing pygments (2.19.1)
poetry: - Installing pyparsing (3.2.3)
poetry: - Installing requests (2.32.3)
poetry: - Installing six (1.17.0)
poetry: - Installing sortedcontainers (2.4.0)
poetry: - Installing typing-extensions (4.13.2)
poetry: - Installing yarl (1.19.0)
poetry: - Installing aiohttp (3.11.16)
poetry: - Installing algokit-utils (4.0.0)
poetry: - Installing algorand-python (2.7.0)
poetry: - Installing cattrs (24.1.3)
poetry: - Installing click (8.1.8)
poetry: - Installing coverage (7.8.0)
poetry: - Installing docstring-parser (0.16)
poetry: - Installing cfgv (3.4.0)
poetry: - Installing cyclonedx-python-lib (9.1.0)
poetry: - Installing ecdsa (0.19.1)
poetry: - Installing cachecontrol (0.14.2)
poetry: - Installing coincurve (21.0.0)
poetry: - Installing identify (2.6.9)
poetry: - Installing immutabledict (4.2.1)
poetry: - Installing mypy-extensions (1.0.0)
poetry: - Installing networkx (3.4.2)
poetry: - Installing nodeenv (1.9.1)
poetry: - Installing pathspec (0.12.1)
poetry: - Installing pip-api (0.0.34)
poetry: - Installing pip-requirements-parser (32.0.1)
poetry: - Installing pytest (8.3.5)
poetry: - Installing pyyaml (6.0.2)
poetry: - Installing rich (14.0.0)
poetry: - Installing structlog (25.2.0)
poetry: - Installing toml (0.10.2)
poetry: - Installing virtualenv (20.30.0)
poetry: - Installing algokit-client-generator (2.1.0)
poetry: - Installing pip-audit (2.9.0)
poetry: - Installing puyapy (4.7.0)
poetry: - Installing algorand-python-testing (0.4.1)
poetry: - Installing black (25.1.0)
poetry: - Installing pre-commit (4.2.0)
poetry: - Installing python-dotenv (1.1.0)
poetry: - Installing mypy (1.15.0)
poetry: - Installing ruff (0.9.10)
poetry: - Installing pytest-cov (6.1.1)
poetry: 
poetry: Installing the current project: algorand-python-workshop (0.1.0)
poetry: 
poetry: Error: The current project could not be installed: No file/folder found for package algorand-python-workshop
poetry: If you do not want to install the current project use --no-root.
poetry: If you want to use Poetry only for dependency management but not for packaging, you can disable package mode by setting package-mode = false in your pyproject.toml file.
poetry: If you did intend to install the current project, you may need to set `packages` in your pyproject.toml file.
poetry: 
Finished bootstrapping /Users/pedrocardoso/Projects/Algorand/workshop/algorand-python-workshop
pedrocardoso@Pedros-Air algorand-python-workshop % algokit project run build    
You are using AlgoKit version 2.6.2, however version 2.7.0 is available. Please update using `brew upgrade algokit`.
Running commands concurrently.
⏳ algorand-python-workshop: 'build' command in progress...
✅ algorand-python-workshop: 'poetry run python -m smart_contracts build' executed successfully.
pedrocardoso@Pedros-Air algorand-python-workshop % algokit project deploy localnet 
You are using AlgoKit version 2.6.2, however version 2.7.0 is available. Please update using `brew upgrade algokit`.
Using deploy command: /Users/pedrocardoso/.local/bin/poetry run python -m smart_contracts deploy
Loading deployment environment variables...
Deploying smart contracts from AlgoKit compliant repository 🚀
/Users/pedrocardoso/.local/bin/poetry: 2025-05-31 18:40:38,294 INFO      : Loading .env
/Users/pedrocardoso/.local/bin/poetry: 2025-05-31 18:40:38,296 INFO      : Deploying app personal_bank
pedrocardoso@Pedros-Air algorand-python-workshop % 
