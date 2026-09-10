# pagebrew

My tiny static site generator, ~100 lines of Python

## Features

- Index page with post list by date
- RSS feed generation
- Markdown posts with fenced code and tables
- Single template, plain str.format, no Jinja

## Usage

```bash
mkdir posts && echo '# hello' > posts/first.md
python build.py
# site lands in dist/
```

## Installation

```bash
pip install -r requirements.txt
```

## Project structure

```text
├── .github/
│   └── workflows/
│       └── ci.yml
├── docs/
│   ├── configuration.md
│   ├── development.md
│   └── roadmap.md
├── examples/
│   └── quickstart.md
├── .gitattributes
├── .gitignore
├── CHANGELOG.md
├── CONTRIBUTING.md
├── LICENSE
├── SECURITY.md
├── build.py
└── requirements.txt
```

## Development

```bash
python -m venv .venv && source .venv/bin/activate
pip install -r requirements.txt
```

## 说明

个人练习项目, 谨慎用于生产环境。

## License

MIT - see [LICENSE](LICENSE).
