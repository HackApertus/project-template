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

Pick the directory for your track. **Its contents become the root of your
repository.** Move everything inside it (`README.md`, `technical_report.md`,
`Makefile`, `src/`, …, including hidden files like `.gitignore`) to the top
level, and delete all the `track_*` directories. Keep the files and
directories as shown below.

Don't nest your project in a subdirectory. We run `make run` from the root of
your repository, so the `Makefile` has to be there.

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

`make run` has to spin up your project from the root of your repository, on a
clean checkout:

```bash
git clone <your-repo>
cd <your-repo>
make run
```

## Getting started

1. Click **Use this template** to create your own repository.
2. Move the contents of your track's directory (e.g. `track_1a/`) to the
   repository root, then delete all the `track_*` directories.
3. Fill in `README.md` and `technical_report.md`.
4. Make sure `make run` works from the repository root, on a clean checkout.

## License

All Hack Apertus projects are open-sourced. Please check our Terms & Conditions for specific licensing details (6. What you build is open source): https://hackapertus.ch/terms-and-conditions
