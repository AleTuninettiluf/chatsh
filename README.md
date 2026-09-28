# chatsh

Tiny streaming CLI for OpenAI-compatible chat APIs

## Examples

```bash
chatsh explain this error < error.log
cat diff.patch | chatsh review this diff
```

## Highlights

- Streams tokens as they arrive
- Model and system prompt via flags or env
- Reads the prompt from args or stdin
- Works with any OpenAI-compatible endpoint

## Installation

```bash
pip install -r requirements.txt
export OPENAI_API_KEY=sk-...
```

## Project structure

```text
├── .github/
│   └── workflows/
│       └── ci.yml
├── docs/
│   ├── configuration.md
│   ├── faq.md
│   └── usage.md
├── examples/
│   └── quickstart.md
├── tests/
│   └── test_smoke.py
├── .gitignore
├── CONTRIBUTING.md
├── LICENSE
├── SECURITY.md
├── chatsh.py
└── requirements.txt
```

## Notes

- mostly stable, edge cases remain

## License

MIT. Do whatever you want.
