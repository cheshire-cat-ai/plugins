# The Cheshire Cat Plugin Directory

Welcome to the official plugin directory for **The Cheshire Cat**. This repository contains a curated list of plugins that extend the functionality of The Cheshire Cat. Plugin authors are encouraged to contribute their awesome creations to this directory following the guidelines outlined below.

This comprises a collection of officially endorsed plugins, curated by the community. However, please note that you have complete freedom to create and share your own plugins anywhere and in any preferred format, including .zip files or private repositories, even if they are not listed here.

## How to Contribute a Plugin

To add your plugin to the directory, you need to submit a Pull Request (PR) with the necessary information about your plugin. Please ensure your plugin meets the following requirements:

1. **Open Source and Hosted on GitHub**: Your plugin must be open-source and hosted on GitHub. This ensures transparency and allows users to access the source code easily.

2. **JSON Format**: The repository follows a specific JSON format for consistency. The structure of the JSON object look like this, add your as **last** object of the JSON:

```json
{
  "0": {
    "name": "Plugin name",
    "url": "https://link-to-the-repository"
  },
  "1": {
    "name": "Plugin name",
    "url": "https://link-to-the-repository"
  },
  "2": {
    "name": "Your awesome plugin name here",
    "url": "https://link-to-the-repository"
  }
}
```

3. **Malicious Code Check**: Our team will conduct a quick review of your plugin to check for any potential malicious code. This is to ensure the safety and security of all users in the community.

## How to Submit a Pull Request

To submit a PR, please follow these steps:

1. Fork this repository to your GitHub account.

2. Clone the forked repository to your local machine.

3. Create a new branch for your plugin.

```bash
git checkout -b add-your-plugin
```

4. Add your plugin entry to the JSON file. Replace the placeholders with your actual plugin details.

```json
"125": {
  "name": "Your awesome plugin name",
  "url": "https://link-to-the-repository"
}
```

5. Commit your changes with a descriptive message.

```bash
git add plugins.json
git commit -m "Add My awesome plugin"
```

6. Push your branch to your GitHub repository.

7. Create a Pull Request (PR) from your forked repository to the main repository (this one). Please provide a clear description of your plugin and any additional information you think is relevant.

8. Wait for the team's review and approval. We'll try to be as prompt as possible!

## Code of Conduct

As a contributor to The Cheshire Cat Plugin Directory, we expect you to follow our [Code of Conduct](https://github.com/cheshire-cat-ai/core/blob/main/readme/CODE-OF-ETHICS.md) at all times. Let's maintain a friendly and welcoming community for everyone.

## Stay Updated

The plugin directory is likely to grow over time with more exciting contributions. To stay updated, consider starring and following this repository. Additionally, feel free to open issues or discussions for any suggestions, bug reports, or general feedback.

Thank you for contributing to The Cheshire Cat Plugin Directory! Happy coding! 😺🎉
