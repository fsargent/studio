# Publishing in Studio

When changes are made to your API descriptions or Markdown documentation, whether that is done in Stoplight Studio or anywhere else, you want to get those changes reflected in Documentation, Mock Servers, Explorer, etc.

The publishing method you use depends on your project type:

* **Git Projects**: [Connect your Git repository](../02-git-credentials.md) and make updates automatically in Stoplight whenever changes are made within Studio or another editor, such as VS code. See [Publish Git Projects](https://meta.stoplight.io/docs/platform/ZG9jOjM0MjE2NTA5-git-projects).
* **Stoplight Projects**: Publish changes as soon as they are made in Studio Web. This method is not available in Studio Desktop. See [Publish Stoplight Projects](https://meta.stoplight.io/docs/platform/ZG9jOjM0MjIzMjI0-stoplight-projects).
* **CLI Projects**: Use the Stoplight CLI to publish local projects, projects that do not use Git, or to facilitate continuous integration. You can also use the Stoplight CLI to automate publishing directly from any Git provider. We simplify this for GitHub by providing a GitHub Workflow. See Publish with the Stoplight CLI. See [Publish with the Stoplight CLI](https://meta.stoplight.io/docs/platform/ZG9jOjQ1NTQxMw-stoplight-cli).

Note that nodeJS version 12 or greater is required to run the Stoplight CLI. You can verify your version using the command: `node --version`

## Learn More
* [Publish Overview](https://meta.stoplight.io/docs/platform/ZG9jOjQ1NTQxNA-publishing) 
* [Add Projects in Studio Web](https://meta.stoplight.io/docs/platform/ZG9jOjE4ODEyMw-add-projects)
* [Add Projects in Studio Desktop](../Basics/01-working-with-projects.md)
