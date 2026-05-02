# Framework Attachments

![Cover](cover.png)

Attach files and data to test reports.

## What's Inside

- `procedure.yaml`: defines two phases
- `phases/collect_data.py`: builds JSON in memory and attaches it
- `phases/capture_logs.py`: writes a temp log file and attaches it from disk
- `pyproject.toml`: uv-managed Python project

## Get Started

1. Sign up for a free TofuPilot account at [tofupilot.app](https://www.tofupilot.app/auth/signup).
2. Open the **New Procedure** flow in the dashboard and clone this template.
3. Follow the dashboard's instructions to set up a station and run the procedure.

For deeper guides, see the [TofuPilot docs](https://www.tofupilot.com/docs/framework).

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
