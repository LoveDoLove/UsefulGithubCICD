# UsefulGithubCICD

A collection of practical GitHub Actions workflows, templates, and automation utilities to streamline CI/CD processes for your repositories. This project provides ready-to-use workflows for cleaning up failed runs, resetting all actions, and more, making it easier to maintain healthy and efficient GitHub repositories.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](./LICENSE)
[![GitHub Sponsors](https://img.shields.io/badge/sponsor-LoveDoLove-blue?logo=github)](https://github.com/sponsors/LoveDoLove)

---

## Table of Contents
- [About](#about)
- [Workflows](#workflows)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Funding](#funding)
- [Acknowledgments](#acknowledgments)

---

## About

This repository is designed to help you manage and automate your GitHub repositories with useful CI/CD workflows. It includes:
- Automated cleanup of failed workflow runs
- Resetting/cancelling all in-progress and queued workflows
- Templates and best practices for GitHub Actions

These tools help keep your repository clean and your CI/CD pipelines running smoothly.

---

## Workflows

### 1. Cleanup Failed Runs
Deletes up to 100 of the most recent failed workflow runs to keep your repository tidy.
- **File:** `.github/workflows/cleanup_failed_actions.yml`
- **Trigger:** Manual (`workflow_dispatch`)

### 2. Reset All Actions
Cancels all in-progress and queued workflow runs for the repository.
- **File:** `.github/workflows/reset_all_actions.yml`
- **Trigger:** Manual (`workflow_dispatch`)

---

## Getting Started

To use these workflows in your own repository:

1. **Copy the workflow files** from `.github/workflows/` to your repository's `.github/workflows/` directory.
2. **Customize as needed** (e.g., permissions, workflow names).
3. **Trigger manually** from the GitHub Actions tab using the `Run workflow` button.

### Prerequisites
- A GitHub repository with Actions enabled
- Sufficient permissions to run and manage workflows

---

## Usage

- **Cleanup Failed Runs:**
  - Go to the Actions tab in your repository
  - Select `Cleanup Failed Runs` workflow
  - Click `Run workflow` to delete failed runs

- **Reset All Actions:**
  - Go to the Actions tab
  - Select `Reset All Actions` workflow
  - Click `Run workflow` to cancel all in-progress and queued runs

---

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request. For major changes, open an issue first to discuss what you would like to change.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/YourFeature`)
3. Commit your changes (`git commit -m 'Add some feature'`)
4. Push to the branch (`git push origin feature/YourFeature`)
5. Open a pull request

---

## License

This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for details.

---

## Funding

If you find this project useful, consider sponsoring via [GitHub Sponsors](https://github.com/sponsors/LoveDoLove) or check the [FUNDING.yml](.github/FUNDING.yml) for more options.

---

## Acknowledgments

- [GitHub Actions Documentation](https://docs.github.com/en/actions)
- [Best-README-Template](https://github.com/othneildrew/Best-README-Template)

---

<p align="right">(<a href="#top">back to top</a>)</p>
