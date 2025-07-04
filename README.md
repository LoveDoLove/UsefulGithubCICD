<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->
<a id="readme-top"></a>

<!-- PROJECT SHIELDS -->
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]

<br />
<div align="center">
  <h1>Useful Github CI/CD Cleanup Workflows</h1>
  <p>
    Reusable GitHub Actions workflows for automating repository maintenance and CI/CD cleanup tasks.
    <br />
    <a href="https://github.com/LoveDoLove/UsefulGithubCICD"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="#usage">View Demo</a>
    ·
    <a href="https://github.com/LoveDoLove/UsefulGithubCICD/issues">Report Bug</a>
    ·
    <a href="https://github.com/LoveDoLove/UsefulGithubCICD/issues">Request Feature</a>
  </p>
</div>

---

## Table of Contents
- [About The Project](#about-the-project)
- [Features](#features)
- [Workflows](#workflows)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)
- [Acknowledgments](#acknowledgments)

---

## About The Project

This project provides a set of reusable GitHub Actions workflows for cleaning up workflow runs in your repository. These workflows help maintain a healthy and efficient CI/CD environment by automating routine cleanup tasks, saving storage, and improving visibility of important runs.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Features
- **Cleanup Failed Runs:** Deletes up to 100 of the most recent failed workflow runs.
- **Cleanup All Actions:** Deletes all workflow runs except the currently running one.
- Easy to integrate into any repository.
- Manual trigger for safe and controlled cleanup.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Workflows

### 1. Cleanup Failed Runs
- **File:** `actions/workflows/cleanup_failed_actions.yml`
- **Trigger:** Manual (`workflow_dispatch`)
- **Description:** Deletes up to 100 of the most recent failed workflow runs in the repository.

### 2. Cleanup All Actions
- **File:** `actions/workflows/cleanup_all_actions.yml`
- **Trigger:** Manual (`workflow_dispatch`)
- **Description:** Deletes all workflow runs except the currently running one.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Getting Started

To use these workflows in your own repository:

### Prerequisites
- A GitHub repository with Actions enabled
- Sufficient permissions to run and manage workflows

### Installation
1. **Copy the workflow files** from `actions/workflows/` to your repository's `.github/workflows/` directory.
2. **Customize as needed** (e.g., permissions, workflow names).
3. **Trigger manually** from the GitHub Actions tab using the `Run workflow` button.

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
