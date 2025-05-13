<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->
<a id="readme-top"></a>

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![GitHub Sponsors](https://img.shields.io/badge/sponsor-LoveDoLove-blue?logo=github)](https://github.com/sponsors/LoveDoLove)

---

# UsefulGithubCICD

A collection of practical GitHub Actions workflows, templates, and automation utilities to streamline CI/CD processes for your repositories. This project provides ready-to-use workflows for cleaning up failed runs, resetting all actions, and more, making it easier to maintain healthy and efficient GitHub repositories.

---

## Table of Contents
- [About](#about-the-project)
- [Workflows](#workflows)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Roadmap](#roadmap)
- [Contributing](#contributing)
- [License](#license)
- [Funding](#funding)
- [Contact](#contact)
- [Acknowledgments](#acknowledgments)

---

## About The Project

This repository provides a set of reusable GitHub Actions workflows for cleaning up workflow runs, managing failed actions, and automating repository maintenance. Inspired by [othneildrew/Best-README-Template](https://github.com/othneildrew/Best-README-Template), this project is tailored and maintained by [LoveDoLove](https://github.com/LoveDoLove).

Use these templates to:
* Automate cleanup of failed or all workflow runs
* Maintain a clean and efficient CI/CD environment
* Quickly bootstrap new repositories with best-practice workflows

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Built With

* [GitHub Actions](https://github.com/features/actions)
* [actions/github-script](https://github.com/actions/github-script)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Workflows

### 1. Cleanup Failed Runs
Deletes up to 100 of the most recent failed workflow runs to keep your repository tidy.
- **File:** `.github/workflows/cleanup_failed_actions.yml`
- **Trigger:** Manual (`workflow_dispatch`)

### 2. Cleanup All Actions
Deletes all workflow runs except the currently running one.
- **File:** `.github/workflows/cleanup_all_actions.yml`
- **Trigger:** Manual (`workflow_dispatch`)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Getting Started

To use these workflows in your own repository:

1. **Copy the workflow files** from `.github/workflows/` to your repository's `.github/workflows/` directory.
2. **Customize as needed** (e.g., permissions, workflow names).
3. **Trigger manually** from the GitHub Actions tab using the `Run workflow` button.

### Prerequisites
- A GitHub repository with Actions enabled
- Sufficient permissions to run and manage workflows

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Usage

- **Cleanup Failed Runs:**
  - Go to the Actions tab in your repository
  - Select `Cleanup Failed Runs` workflow
  - Click `Run workflow` to delete failed runs

- **Cleanup All Actions:**
  - Go to the Actions tab
  - Select `Cleanup All Actions` workflow
  - Click `Run workflow` to delete all runs except the current one

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Roadmap

- [x] Add cleanup workflows for all and failed runs
- [ ] Add more automation templates
- [ ] Add documentation for advanced usage

See the [open issues](https://github.com/LoveDoLove/UsefulGithubCICD/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## License

Distributed under the MIT License. See `LICENSE` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Funding

If you find this project useful, consider sponsoring via [GitHub Sponsors](https://github.com/sponsors/LoveDoLove) or check the [FUNDING.yml](.github/FUNDING.yml) for more options.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Contact

LoveDoLove - [GitHub](https://github.com/LoveDoLove)

Project Link: [https://github.com/LoveDoLove/UsefulGithubCICD](https://github.com/LoveDoLove/UsefulGithubCICD)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Acknowledgments

- [othneildrew/Best-README-Template](https://github.com/othneildrew/Best-README-Template) (template inspiration)
- [actions/github-script](https://github.com/actions/github-script)
- [GitHub Actions Documentation](https://docs.github.com/en/actions)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->
[contributors-shield]: https://img.shields.io/github/contributors/LoveDoLove/UsefulGithubCICD.svg?style=for-the-badge
[contributors-url]: https://github.com/LoveDoLove/UsefulGithubCICD/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/LoveDoLove/UsefulGithubCICD.svg?style=for-the-badge
[forks-url]: https://github.com/LoveDoLove/UsefulGithubCICD/network/members
[stars-shield]: https://img.shields.io/github/stars/LoveDoLove/UsefulGithubCICD.svg?style=for-the-badge
[stars-url]: https://github.com/LoveDoLove/UsefulGithubCICD/stargazers
[issues-shield]: https://img.shields.io/github/issues/LoveDoLove/UsefulGithubCICD.svg?style=for-the-badge
[issues-url]: https://github.com/LoveDoLove/UsefulGithubCICD/issues
[license-shield]: https://img.shields.io/github/license/LoveDoLove/UsefulGithubCICD.svg?style=for-the-badge
[license-url]: https://github.com/LoveDoLove/UsefulGithubCICD/blob/main/LICENSE
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/LoveDoLove
