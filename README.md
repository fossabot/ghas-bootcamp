<h1 align="center">GitHub Advanced Security Bootcamp</h1>
<p align="center">
  <a href="#mega-prerequisites">Prerequisites</a> •  
  <a href="#books-resources">Resources</a>
</p>

> This bootcamp is designed to get you familiar with GitHub Advanced Security (GHAS) so that you can better understand how to use it in your own repositories.

## :mega: Prerequisites
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Fcmboling%2Fghas-bootcamp.svg?type=shield)](https://app.fossa.com/projects/git%2Bgithub.com%2Fcmboling%2Fghas-bootcamp?ref=badge_shield)

To participate in the workshop you need a GitHub account and need to be invited to the workshop organization [ghas-bootcamp](https://github.com/ghas-bootcamp). If your repository hasn't been automatically created in the workshop organization, either click `Use this template` and create a repository under this organization, or create a new repository and push a copy of the `ghas-bootcamp` repository.

```bash
git clone https://github.com/ghas-bootcamp/ghas-bootcamp.git
cd ghas-bootcamp
git remote set-url origin git@github.com:{org-or-username}/{repo-name}.git
```

## 🏫 Agenda

We will go over the following topics:

<details>
<summary>Day One </summary>

#### Day One Learning
- [x] Comprenhensive overview of GHAS
- [x] Securing your supply chain with Dependency management
- [x] Secret scanning
- [x] Rolling out GHAS in your organization
- [x] Q&A

#### Day One: Secret Scanning and Dependabot Exercises
##### Secret scanning
- [x] Enabling secret scanning
- [x] Viewing and managing results
- [x] Excluding files from secret scanning
- [x] Custom patterns for secret scanning
- [x] Managing access to alerts

##### Dependabot
- [x] Enabling Dependabot alerts
- [x] Reviewing the dependency graph
- [x] Viewing and managing results
- [x] Enabling Dependabot security updates
- [x] Configuring Dependabot security updates
- [x] Working with Dependency Review
</details>

<details>
<summary>Day Two </summary>

#### Day Two Learning
- [x] Explore how code scanning works
- [x] What is Security Overview?
- [x] CodeQL Demo
- [x] Final Q&A

#### Day Two: Code Scanning + CodeQL Demo
##### Code scanning
- [x] Enabling code scanning
- [x] Reviewing any failed analysis job
- [x] Using context and expressions to modify build
- [x] Reviewing and managing results
- [x] Triaging a result in a PR
- [x] Customizing CodeQL Configuration
- [x] Adding your own code scanning suite to exclude rules
- [x] Understanding how to add a custom query
- [x] CodeQL Demo

</details>

## :books: Resources
- [About code scanning](https://docs.github.com/en/github/finding-security-vulnerabilities-and-errors-in-your-code/about-code-scanning)
- [About dependency scanning](https://docs.github.com/en/free-pro-team@latest/github/managing-security-vulnerabilities/about-alerts-for-vulnerable-dependencies)
- [About secret scanning](https://docs.github.com/en/github/administering-a-repository/about-secret-scanning)
- [Action events that trigger workflows](https://docs.github.com/en/free-pro-team@latest/actions/reference/events-that-trigger-workflows)
- [Configuring builds for compiled languages](
https://docs.github.com/en/free-pro-team@latest/github/finding-security-vulnerabilities-and-errors-in-your-code/configuring-the-codeql-workflow-for-compiled-languages)
- [Configuring code scanning](https://docs.github.com/en/free-pro-team@latest/github/finding-security-vulnerabilities-and-errors-in-your-code/configuring-code-scanning)
- [Configuring notifications for dependabot alerts](https://docs.github.com/en/free-pro-team@latest/github/managing-security-vulnerabilities/configuring-notifications-for-vulnerable-dependencies#configuring-notifications-for-dependabot-alerts)
- [Customizing dependency updates](https://docs.github.com/en/free-pro-team@latest/github/administering-a-repository/customizing-dependency-updates)
- [Dependency update configuration options](https://docs.github.com/en/free-pro-team@latest/github/administering-a-repository/configuration-options-for-dependency-updates)
- [Filter pattern cheat sheet](https://docs.github.com/en/free-pro-team@latest/actions/reference/workflow-syntax-for-github-actions#filter-pattern-cheat-sheet)
- [Running additional queries](
https://docs.github.com/en/free-pro-team@latest/github/finding-security-vulnerabilities-and-errors-in-your-code/configuring-code-scanning#running-additional-queries)
- [Troubleshooting code scanning workflow](https://docs.github.com/en/free-pro-team@latest/github/finding-security-vulnerabilities-and-errors-in-your-code/troubleshooting-the-codeql-workflow)
- [Code scanning API](https://docs.github.com/en/free-pro-team@latest/rest/reference/code-scanning)
- [Secret scanning API](https://docs.github.com/en/rest/reference/secret-scanning)
- [GraphQL API](https://docs.github.com/en/free-pro-team@latest/graphql)
  - [RepositoryVulnerabilityAlert](https://docs.github.com/en/free-pro-team@latest/graphql/reference/objects#repositoryvulnerabilityalert)
- [REST API](https://docs.github.com/en/free-pro-team@latest/rest)


## License
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Fcmboling%2Fghas-bootcamp.svg?type=large)](https://app.fossa.com/projects/git%2Bgithub.com%2Fcmboling%2Fghas-bootcamp?ref=badge_large)