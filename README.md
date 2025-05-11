# UsefulGithubCICD

A collection of helpful GitHub Actions workflows designed to streamline continuous integration and deployment (CI/CD) for your repositories.

## Features

- **Cleanup Failed Runs** (`cleanup_failed_actions.yml`): Automatically delete failed workflow runs to keep your Actions history clean.
- (Coming soon) More workflows to manage releases, dependencies, security scans, and more.

## Installation

Simply copy the workflow file(s) you need into your repository’s `.github/workflows/` directory:

```bash
cp path/to/UsefulGithubCICD/.github/workflows/<workflow-file>.yml .github/workflows/
``` 

Alternatively, reference a workflow directly from this repository:

```yaml
# .github/workflows/cleanup_failed_actions.yml
name: Cleanup Failed Runs
on:
  workflow_dispatch:

jobs:
  cleanup:
    uses: <YOUR_GITHUB_USERNAME>/UsefulGithubCICD/.github/workflows/cleanup_failed_actions.yml@main
    with:
      GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```

## Usage

1. Add or reference the workflow in your project.
2. Provide any required inputs or permissions as documented in each workflow file.
3. Trigger the workflow manually or on your preferred GitHub events.

## Available Workflows

| File                             | Description                                     |
|----------------------------------|-------------------------------------------------| 
| `cleanup_failed_actions.yml`     | Deletes all failed workflow runs on-demand.     |

*(Contributions to expand this list are welcome!)*

## Contributing

Contributions are highly appreciated:

1. Fork this repository.
2. Create a new branch for your feature or fix.
3. Add or update workflow YAML files under `.github/workflows/`.
4. Test your changes.
5. Submit a pull request detailing your improvements.

Please follow standard [GitHub Flow](https://guides.github.com/introduction/flow/) and adhere to best practices for Actions workflows.

## License

This project is licensed under the [MIT License](LICENSE).

## Contact

Maintained by [Your Name] — feel free to open issues or pull requests with questions or suggestions.
