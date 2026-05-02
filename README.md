# Framework Attachments

![Cover](cover.png)

Two-phase Framework procedure showing how to attach files and in-memory data to a test report.

## What's Inside

- `procedure.yaml`: defines two phases
- `phases/collect_data.py`: builds JSON in memory and attaches it
- `phases/capture_logs.py`: writes a temp log file and attaches it from disk
- `pyproject.toml`: uv-managed Python project

## Use This Template

Clone it from the **New Procedure** flow in TofuPilot. TofuPilot creates the repository in your account, links a procedure, builds the first deployment, and pushes it to a station.

## Structure

```
.
├── procedure.yaml
├── phases/
│   ├── collect_data.py
│   └── capture_logs.py
├── pyproject.toml
└── README.md
```

## Key Concepts

- **`attach.data(bytes, filename)`**: attach an in-memory blob (e.g. JSON, CSV, screenshot bytes)
- **`attach.file(path, filename)`**: attach a file from disk by path
- Attachments appear on the test report after the run uploads

## Next Steps

See the [TofuPilot guides](https://www.tofupilot.com/guides) for more templates.
