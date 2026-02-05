# ad-reco-bidding-pacing

Ad recommendation bidding & pacing experiments / services.

## Project structure

```
.
├── configs/                     # config files (checked-in examples)
├── docs/                        # project docs
├── scripts/                     # one-off scripts / utilities
├── src/
│   └── ad_reco_bidding_pacing/  # python package
└── tests/                       # unit tests
```

## Development

- Sync deps (creates `.venv`) then run tests:
  - `uv sync --dev`
  - `uv run pytest`

Note: the first `uv sync` needs network access to download packages.
