````markdown name=README.md url=https://github.com/RanRhoads84/Auto-Video-Encoder/blob/main/README.md
# Auto Video Encoder

Auto Video Encoder is a small collection of tools and scripts for automated video encoding on Linux. The repository contains a focused subproject (linux-video-encoder) that implements the encoder application, configuration, and helper scripts.

This top-level README gives an overview of the repository structure, installation pointers, configuration notes, and links to the main subproject documentation.

## Repository layout

- linux-video-encoder/
  - README.md — Detailed README for the encoder subproject (installation, usage, examples).
  - config.json — Example/default configuration used by the encoder.
  - pyproject.toml — Python packaging / dependency metadata (project uses standard Python tooling).
  - scripts/ — Helper shell/Python scripts used by the project.
  - src/ — Source code for the encoder.
  - LICENSE — License for the encoder subproject.

See linux-video-encoder/README.md for the primary, runnable documentation and usage examples.

## Key points

- Language: Python (see pyproject.toml for dependencies and tooling configuration).
- Purpose: Automate video encoding tasks (batch processing, configuration-driven).
- Target environment: Linux (scripts and tooling assume a Linux environment).

## Quick start

1. Read the linux-video-encoder README:
   - linux-video-encoder/README.md

2. Inspect and adapt the configuration:
   - linux-video-encoder/config.json

3. Install dependencies and run:
   - The project includes a pyproject.toml for standard Python install workflows (poetry, pip with build tools, etc.). See linux-video-encoder/README.md for detailed install commands.

4. Run encoder scripts from linux-video-encoder/scripts or run the main entry point in linux-video-encoder/src as described in the subproject README.

## Configuration

Configuration is driven by the example config file at:
- linux-video-encoder/config.json

Open that JSON file to customize input directories, output directories, codec settings, bitrates, and other encoding options. The subproject README explains each option and recommended values.

## Development

- Source code is under linux-video-encoder/src.
- Helper scripts are in linux-video-encoder/scripts.
- Use the pyproject.toml to set up virtual environments and manage dependencies.

## License

The encoder subproject includes a LICENSE file:
- linux-video-encoder/LICENSE

Check that file for the full licensing terms.

## Contributing

If you want to contribute:
- Read linux-video-encoder/README.md for development setup and testing instructions.
- Open an issue or a pull request with a clear description of changes or proposed features.
- Follow the repository's coding and commit message conventions (see subproject README for details if present).

## Where to find more details

For use, installation commands, exact configuration keys, and examples, see the subproject README:
- linux-video-encoder/README.md

If you want, I can generate or update a more detailed top-level README that includes step-by-step installation instructions (apt/ffmpeg prerequisites, virtualenv/poetry commands), example config snippets from linux-video-encoder/config.json, and example commands to run the encoder. Tell me which sections you'd like expanded.
````
