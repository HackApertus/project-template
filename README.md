# Hack Apertus — project template

Template repository for [Hack Apertus](https://hackapertus.ch/) submissions.
Every project keeps almost the same layout, so organizers and judges find the
same things in the same place.

## Select your track

This repository holds one example project per track:

- `track_1a/`
- `track_1b/`
- `track_2a/`
- `track_2b/`

Keep the directory for the track you are competing in **exactly as it is** —
don't rename it or move its files — and delete the other track directories.
That directory is your project root. Keep the files and directories as shown
below.

## The structure

| Path | What it is |
| --- | --- |
| `README.md` | Your project write-up — fill in every section |
| `technical_report.md` | The deeper write-up: architecture, evaluation, limitations |
| `Makefile` | `make run` must spin up your project |
| `src/` | Your code |
| `data/` | Datasets — `track_1a`, `track_2a` and `track_2b` only |
| `docs/` | Diagrams, notes, longer write-ups |

Store your data in `data/` and commit it with your project. If it is too big
for git (GitHub rejects files over 100 MB), upload it to
[Hugging Face](https://huggingface.co/) instead and link it from
`technical_report.md`, together with where the data came from.

## Run it

Judges run `make run` from inside your track directory, on a clean checkout:

```bash
git clone <your-repo>
cd <your-repo>/track_1a   # your track directory
make run
```

## Getting started

1. Click **Use this template** to create your own repository.
2. Delete the other track directories. Don't rename or restructure yours.
3. Fill in its `README.md` and `technical_report.md`.
4. Make `make run` work from inside your track directory, on a clean checkout.

## License

All Hack Apertus projects are open-sourced. Please check our Terms & Conditions for specific licensing details (6. What you build is open source): https://hackapertus.ch/terms-and-conditions
