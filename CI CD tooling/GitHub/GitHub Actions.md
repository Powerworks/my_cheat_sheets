The concept of **Continuous Integration (CI)** involves the continuous merging of new code with the existing codebase of a project. This approach is particularly valuable for early bug detection and facilitates cost-effective bug fixes.

**GitHub** offers a feature known as “Actions.” These Actions enable the automation, customization, and execution of development workflows directly from the code repository. You can configure the **Continuous Integration (CI) process using GitHub Actions.**

GitHub Actions serves as GitHub’s CI/CD pipeline tool. It is designed for open-source use, so the build is not tied to any specific technology.

There is no official online editor for build pipelines, so you can use any text editor in a cloned repository and deploy updates to the **Git repository.**

This method requires careful monitoring of the settings for the build steps used.

Variables, also referred to as secrets, are values that can be stored globally or per environment on **GitHub.**

After entering the value of a secret, it cannot be viewed again, but it can be used in Actions.

While there are no specific tools for environment hooks, you can use secrets to publish profiles on [Azure Web Apps to accomplish similar tasks.](https://datascientest.com/en/what-you-didnt-know-about-azure-databricks)

## GitHub Actions

Automate, customize, and execute your software development workflows right in your repository with GitHub Actions ([[repos/cheat-sheets/misc/github-actions]]). You can discover, create, and share actions to perform any job you'd like, including CI/CD, and combine actions in a completely customized workflow.
