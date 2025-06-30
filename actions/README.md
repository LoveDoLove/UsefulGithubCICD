<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->
<a id="readme-top"></a>

# GitHub Actions Workflows

This directory contains reusable GitHub Actions workflows for automating repository maintenance and CI/CD cleanup tasks. These workflows are designed to help you keep your repository clean by removing failed or all workflow runs, saving storage, and improving visibility of important runs.

---

## Table of Contents
- [About](#about-the-project)
- [Workflows](#workflows)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)
- [Acknowledgments](#acknowledgments)

---

## About The Project

This folder provides a set of GitHub Actions workflows for cleaning up workflow runs:
- **cleanup_failed_actions.yml**: Deletes up to 100 of the most recent failed workflow runs.
- **cleanup_all_actions.yml**: Deletes all workflow runs except the currently running one.

These workflows help maintain a healthy and efficient CI/CD environment by automating routine cleanup tasks.

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

1. **Copy the workflow files** from `actions/workflows/` to your repository's `.github/workflows/` directory.
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

Distributed under the MIT License. See `../../LICENSE` for more information.

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
