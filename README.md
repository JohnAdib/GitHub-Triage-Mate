# TriageMate 

This repository contains GitHub Actions workflows to automate the triaging process for pull requests, add relevant tags based on file changes, and assign the pull request to the person who created it. Additionally, it provides examples of pull requests, templates for issues, and a cleanup process to remove the GitHub Actions cache after the repository is closed.

## How It Works

### Pull Request Triage and Tagging

When a pull request is created or updated, the GitHub Actions workflows in this repository automatically:

1. **Triage the Pull Request:** The workflow triages the pull request based on predefined criteria, such as labels, comments, and file changes.
2. **Add Related Tags:** Relevant tags are added based on the changes made in the files. For example, if the pull request modifies frontend files, the 'frontend' tag will be added.
3. **Assign to Creator:** The pull request is assigned to the person who created it, streamlining the review process.

### Pull Request Example

To understand the expected format and information for pull requests, refer to the [Pull Request Example](./pull_request_example.md) file in this repository.

### Issue Template

When creating issues, please follow the guidelines outlined in the [Issue Template](./issue_template.md) file. This ensures that issues are well-documented and include essential details for efficient problem resolution.

## How to Contribute

We welcome contributions from the community to improve and enhance this repository. Here's how you can contribute:

1. Fork the repository and clone it to your local machine.
2. Make your changes, whether it's improving the documentation, enhancing the workflows, or fixing bugs.
3. Commit your changes and push them to your forked repository.
4. Open a pull request from your branch to the main repository. Be sure to include a clear description of your changes.

## Cleanup Process

To maintain a clean repository, a cleanup process is in place. When the repository is closed, the GitHub Actions cache is automatically removed to free up resources.

## License

This project is licensed under the MIT - see the [LICENSE](LICENSE) file for details.

---

**Note:** If you have any suggestions, improvements, or bug reports, please don't hesitate to contribute. Your help is greatly appreciated!
