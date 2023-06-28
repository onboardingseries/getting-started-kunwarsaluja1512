[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=11397510&assignment_repo_type=AssignmentRepo)
# Assignemnt 1 : Getting Started with Franklin

## Pre-requisites
- You have a GitHub account, and understand Git basics.
- You have a Google account.
- You understand the basic HTML, CSS, and JavaScript.
- You have Node/npm installed for local development.

## Add helix bot to your repo
- Install the [Franklin Bot](https://github.com/apps/helix-bot) on your repo by visiting this link: https://github.com/apps/helix-bot/installations/new

**Note** : In the Repository access settings of the Franklin bot, make sure you select Only select Repositories (not All Repositories). Then select your repo, and click Save.


## Environments
- Preview: https://main--{repo}--onboardingseries.hlx.page/
- Live: https://main--{repo}--onboardingseries.hlx.live/

## Installation

```sh
npm i
```

## Linting

```sh
npm run lint
```

## Local development

1. Create a new repository based on the `helix-project-boilerplate` template and add a mountpoint in the `fstab.yaml`
1. Add the [helix-bot](https://github.com/apps/helix-bot) to the repository
1. Install the [Helix CLI](https://github.com/adobe/helix-cli): `npm install -g @adobe/helix-cli`
1. Start Franklin Proxy: `hlx up` (opens your browser at `http://localhost:3000`)
1. Open the `{repo}` directory in your favorite IDE and start coding :)
