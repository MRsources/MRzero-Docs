The documentation is built and published on every push to the `main` branch by [deploy.yml](.github/workflows/deploy.yml).
You can find it [here](https://mrsources.github.io/MRzero-Docs/).

For editing and testing the documentation offline, install the **uv** python package manager: see https://docs.astral.sh/uv/ or run `pip install uv`.
Then run the following code:

```bash
# Live preview:
uv run jupyter book start --execute

# Build the html docs:
uv run jupyter book build --html --execute
```
