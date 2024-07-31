# GCP Docusaurus Documentation Site

![GitHub branch check runs](https://img.shields.io/github/check-runs/damienjburks/gcp-docusaurus/main)
[![License](https://img.shields.io/github/license/damienjburks/gcp-docusaurus)](https://github.com/damienjburks/gcp-docusaurus/blob/main/LICENSE)
[![Docusaurus](https://img.shields.io/badge/docs-docusaurus-5B9BD5)](https://docusaurus.io/)

This project is a documentation site built with [Docusaurus](https://docusaurus.io/) and deployed using Google Cloud Build.

## Table of Contents

- [Installation](#installation)
- [Development](#development)
- [Build](#build)
- [Deployment](#deployment)
- [License](#license)

## Installation

To install the dependencies for this project, run:

```sh
npm install
```

## Development

To start the development server, run:

```sh
npm run start
```

This will start the Docusaurus development server and open your site in a new browser tab. Most changes are reflected live without having to restart the server.

## Build

To build the static files for the documentation site, run:

```sh
npm run build
```

The static files will be generated in the `build` directory.

## Deployment

This project uses Google Cloud Build for continuous deployment. The build configuration is defined in the `cloudbuild.yaml` file.

To deploy the site, ensure you have set up a Cloud Build trigger in your GCP project that watches for changes in the repository and runs the build steps defined in `cloudbuild.yaml`.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
