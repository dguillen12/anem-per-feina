# Contributing to Anem per feina

Welcome, and thank you for your interest in contributing to Anem per feina!

There are many ways in which you can contribute, beyond writing code. The goal of this document is to provide a high-level overview of how you can get involved.

## How to contribute

1. Fork this very repository (use the `fork` button at the top left)
2. Clone the newly created fork (use the green `clone` button)
   > Remember to [configure your SSH key]()
3. Add this repository remote and name it `common`, use the follow command:

```bash
git remote add common git@github.com:GeeksCAT/anem-per-feina-frontoffice.git
```

4. Fetch the latest changes from the `common` repository:

```bash
git fetch common
```

5. Create your branch from the latest changes of the branch `master` in the `common` remote:

```bash
git checkout common/master -b <your_branch_name>
```

> **Tip:** Use a descriptive name for your branch.

6. Make your changes

7. Commit yout changes

8. Push the commited changes to your fork (the `origin` remote)

```bash
git push origin HEAD
```

9. Go to your fork (on the browser), you'll a big yellow banner offering you to create a pull request to the `common` remote. Click to `Create pull request`

10. Fill the gaps of the pull request template.

> **Tip:** You can reference the issu that you are solving using the `#<issue_number>` format.

11. Be social, you can mention the leader or talk to other people.

## Code of conduct

Please keep the tone polite & professional. For some users a discussion on this project may be their first engagement with the open source community. First impressions count, so let's try to make everyone feel welcome.

Be mindful in the language you choose. As an example, in an environment that is heavily male-dominated, posts that start 'Hey guys,' can come across as unintentionally exclusive. It's just as easy, and more inclusive to use gender neutral language in those situations. (e.g. 'Hey folks,')

The [Django code of conduct](https://www.djangoproject.com/conduct/) gives a fuller set of guidelines for participating in community forums.

Please report unacceptable behavior to info@geekscat.org

## Reporting Issues

Have you identified a reproducible problem? Have a feature request? We want to hear about it!

If you have questions you can ask in the [Slack channel](https://geekscat.slack.com)

### Look For an Existing Issue

Before you create a new issue, please do a search in [open issues](https://github.com/GeeksCAT/anem-per-feina-frontoffice/issues) to see if the issue or feature request has already been filed.

If you find your issue already exists, make relevant comments and add your [reaction](https://github.com/blog/2119-add-reactions-to-pull-requests-issues-and-comments). Use a reaction in place of a "+1" comment:

- 👍 - upvote
- 👎 - downvote

If you cannot find an existing issue that describes your bug or feature, create a new issue using the guidelines below.

### Writing Good Bug Reports and Feature Requests

We have 4 teams, please add the correct label specifying the team.

File a single issue per problem and feature request. Do not enumerate multiple bugs or feature requests in the same issue.

Do not add your issue as a comment to an existing issue unless it's for the identical input. Many issues look similar, but have different causes.

The more information you can provide, the more likely someone will be successful at reproducing the issue and finding a fix.

Please include the following with each issue:

- Your operating system

- Reproducible steps (1... 2... 3...) that cause the issue

- What you expected to see, versus what you actually saw

- Images, animations, or a link to a video showing the issue occurring

- A code snippet that demonstrates the issue or a link to a code repository the developers can easily pull down to recreate the issue locally

  - **Note:** Because the developers need to copy and paste the code snippet, including a code snippet as a media file (i.e. .gif) is not sufficient.

### Final Checklist

Please remember to do the following:

- [ ] Search the issue repository to ensure your report is a new issue

- [ ] Recreate the issue

- [ ] Simplify your code around the issue to better isolate the problem

Don't feel bad if the developers can't reproduce the issue right away. They will simply ask for more information!

## Contributing Fixes

If you are interested in writing code to fix issues,
please see [How to Contribute](https://github.com/microsoft/vscode/wiki/How-to-Contribute) in the wiki.

# Thank You!

Your contributions to open source, large or small, make great projects like this possible. Thank you for taking the time to contribute.
