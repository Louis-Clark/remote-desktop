# Remote Desktop Experiment

This project is a simple experiment that launches a browser-accessible remote desktop using GitHub Actions.

It uses the Docker image from:
- https://hub.docker.com/r/prbinu/novnc-desktop

Which is based on:
- https://github.com/prbinu/novnc-desktop

Full credit for the actual remote desktop implementation goes to the original project authors.

## Usage

1. Fork this repository.
2. Open the Actions tab.
3. Run the **Browser Desktop** workflow.
4. Open the generated Cloudflare tunnel URL.

## Notes

- The desktop is ephemeral and does not persist between workflow runs.
- A new Cloudflare URL is generated for each session.
- This project is intended as an experiment and proof of concept.

## Contributing

Feel free to use, modify, or contribute to the project.
