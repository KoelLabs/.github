# Contributing to Koel Labs
👍🎉 First off, thanks for taking the time to contribute! 🎉👍

We welcome all constructive contributions from bug reports/fixes and feature-requests/pull-requests to documentation/translation/design and general discussion.
The Koel Labs project is about inclusive and diverse pronunciation learning and for that, anyone from any background is a welcome member!

The following is a set of guidelines for contributing to Koel Labs and its repositories hosted [here on GitHub](https://github.com/KoelLabs). 
These are mostly guidelines, not rules.
Use your best judgment, and feel free to propose changes to this document in a pull request.

## TL;DR Plz I just have a question!

First check our [FAQ](#faq). If your question is not answered there, post your question to the relevant repo as an issue or to [this repo](https://github.com/KoelLabs/.github/issues) if it is a general question. Make sure to do a cursory search to see if it has already been answered.

## Table Of Contents

[How Can I Contribute?](#how-can-i-contribute)
  * [Determine the relevant repository](#determine-the-relevant-repository)
  * [Reporting Bugs](#reporting-bugs)
  * [Suggesting Enhancements](#suggesting-enhancements)
  * [Your First Code Contribution](#your-first-code-contribution)

[FAQ](#faq)

[Code of Conduct](#code-of-conduct)

## How Can I Contribute?
### Determine the relevant repository
Koel Labs has a couple of different repositories. Each contains a CONTRIBUTING.md with subproject specific instructions and a DEVELOPMENT.md for instructions for how to setup local development.

- If you would like to contribute to the machine learning aspects (training code, dataset pre-processing and collection, evaluation), checkout the [ML repo](https://github.com/KoelLabs/ML).
- If you would like to contribute to the UX/UI and web application, checkout the [webapp repo](https://github.com/KoelLabs/webapp).
- If you would like to optimize the way we run inference or the algorithms we use to provide feedback, checkout the [server repo](https://github.com/KoelLabs/server). Most likely, you'll want to run it with the webapp repo, so it is recommended to start there instead.

### Reporting Bugs

Start by looking through the [FAQ](#faq) and the [current open issues](https://github.com/search?q=+is%3Aissue+user%3AKoelLabs&type=issues). 
If your bug already has an open issue, post your details there.
Otherwise, open a new issue using the following template:
```md
### Prerequisites
<!-- Put an x between the brackets for each of the steps below to indicate their completion. -->

- [ ] Use a clear and descriptive title for the issue to identify the problem
- [ ] Checked the FAQ for common solutions
- [ ] Checked that your issue isn't already filed

### Description

<!-- Description of the issue -->

### Steps to Reproduce

1. <!-- First Step -->
2. <!-- Second Step -->
3. <!-- and so on… -->

<!-- Include screenshots and animated GIFs which show you following the described steps and clearly demonstrate the problem -->
<!-- If the problem wasn't triggered by a specific action, describe what you were doing before the problem happened -->

**Expected behavior:**

<!-- What you expect to happen -->

**Actual behavior:**

<!-- What actually happens -->
<!-- Screenshots of any error messages in the terminal or browser console -->

**Reproduces how often:**

<!-- Can you reliably reproduce the issue? If not, provide details about how often the problem happens and under which conditions it normally happens. -->

**Did the problem start happening recently:**

<!-- Was this always a problem or did it start happening recently? -->
<!-- If it started recently, approximately when did it start? If running locally, can you pinpoint the first commit where it breaks? -->

**Configuration and environment:**

- Using the hosted version on koellabs.com or running locally with docker or running locally without docker
- Name and version of the OS you're using
- Name and version of the browser you're using

### Additional Information

<!-- Any additional information, configuration or data that might be necessary to reproduce the issue. -->
```

### Suggesting Enhancements
Start by looking through the [existing issues](https://github.com/search?q=+is%3Aissue+user%3AKoelLabs&type=issues). If a similar feature request already exists, add your thoughts to that issue.
Otherwise, open a new issue using the following template (make sure to use a clear and descriptive title):
```md
## Summary

<!-- One paragraph explanation of the feature. -->

## Motivation

<!-- Why are we doing this? What use cases does it support? What is the expected outcome? -->
<!-- A clear and concise description of what the problem being solved is. Ex. I'm always frustrated when... -->

## Describe alternatives you've considered

<!-- A clear and concise description of the alternative solutions you've considered. -->

## Additional context

<!-- Add any other context or screenshots about the feature request here. -->
```

### Your First Code Contribution
Unsure where to start? Each repo will have [issues](https://github.com/search?q=+is%3Aissue+user%3AKoelLabs&type=issues) tagged with `beginner` and `help-wanted`. 
Beginner issues will require a few lines of code and a test or two and are a good way to get familiar with the layout of the code-base.
Help-wanted issues might be a bit more involved.

Once you've identified an issue that no one is assigned to and that you believe you can tackle in a reasonable amount of time, start by reading through the current discussion.
Make sure to ask any clarifying questions you may have.
Then post a comment indicating your desire to take responsibility for the issue with an estimated time commitment:
```md
Hi, I have time to take this issue and can have a well tested pull request ready for review by around the end of the week!
```
Once the issue is assigned to you, fork the repo and start working on the fix. 
Don't hesitate to discuss questions as they come up in the issue.
Once you feel the code is ready for review, submit a pull request to the `main` branch of the appropriate repo.
Make sure to go through the associated Q/A checklist of that repo.

## FAQ
1. Where can I ask for help?
    - Feel free to ask questions in the GitHub issues or reach out to a Koel Labs team member.
      - For ML questions: [Alex](mailto:alex@koellabs.com) or [Aruna](mailto:aruna@koellabs.com)
      - For open-source/project questions: [Alex](mailto:alex@koellabs.com)
      - For design/UI/UX questions: [Ruslan](mailto:ruslan@koellabs.com)
      - Not sure what category: email info@koellabs.com and we will put you in touch with the relevant team member
2. Where can I report security vulnerabilities?
    - Please send an email to info@koellabs.com
3. Are there any style guidelines to adhere to?
    - All code style is handled by auto formatters (prettier, black, etc.) and will automatically run as GitHub actions (each repo also contains instructions for running locally and integrating with your IDE). We do not enforce any code style that is not automatically handled by formatters but will recommend variable/function/class naming changes if appropriate. Present tense is recommended for commit messages but not enforced.

## Code of Conduct

### Our Pledge

We as members, contributors, and leaders pledge to make participation in our
community a harassment-free experience for everyone, regardless of age, body
size, visible or invisible disability, ethnicity, sex characteristics, gender
identity and expression, level of experience, education, socio-economic status,
nationality, personal appearance, race, caste, color, religion, or sexual
identity and orientation.

We pledge to act and interact in ways that contribute to an open, welcoming,
diverse, inclusive, and healthy community.

### Our Standards

Examples of behavior that contributes to a positive environment for our
community include:

* Demonstrating empathy and kindness toward other people
* Being respectful of differing opinions, viewpoints, and experiences
* Giving and gracefully accepting constructive feedback
* Accepting responsibility and apologizing to those affected by our mistakes,
  and learning from the experience
* Focusing on what is best not just for us as individuals, but for the overall
  community

Examples of unacceptable behavior include:

* The use of sexualized language or imagery, and sexual attention or advances of
  any kind
* Trolling, insulting or derogatory comments, and personal or political attacks
* Public or private harassment
* Publishing others' private information, such as a physical or email address,
  without their explicit permission
* Other conduct which could reasonably be considered inappropriate in a
  professional setting

### Enforcement Responsibilities

Community leaders are responsible for clarifying and enforcing our standards of
acceptable behavior and will take appropriate and fair corrective action in
response to any behavior that they deem inappropriate, threatening, offensive,
or harmful.

Community leaders have the right and responsibility to remove, edit, or reject
comments, commits, code, wiki edits, issues, and other contributions that are
not aligned to this Code of Conduct, and will communicate reasons for moderation
decisions when appropriate.

### Scope

This Code of Conduct applies within all community spaces, and also applies when
an individual is officially representing the community in public spaces.
Examples of representing our community include using an official email address,
posting via an official social media account, or acting as an appointed
representative at an online or offline event.

### Enforcement

Instances of abusive, harassing, or otherwise unacceptable behavior may be
reported to the community leaders responsible for enforcement at
info@koellabs.com.
All complaints will be reviewed and investigated promptly and fairly.

All community leaders are obligated to respect the privacy and security of the
reporter of any incident.

### Enforcement Guidelines

Community leaders will follow these Community Impact Guidelines in determining
the consequences for any action they deem in violation of this Code of Conduct:

#### 1. Correction

**Community Impact**: Use of inappropriate language or other behavior deemed
unprofessional or unwelcome in the community.

**Consequence**: A private, written warning from community leaders, providing
clarity around the nature of the violation and an explanation of why the
behavior was inappropriate. A public apology may be requested.

#### 2. Warning

**Community Impact**: A violation through a single incident or series of
actions.

**Consequence**: A warning with consequences for continued behavior. No
interaction with the people involved, including unsolicited interaction with
those enforcing the Code of Conduct, for a specified period of time. This
includes avoiding interactions in community spaces as well as external channels
like social media. Violating these terms may lead to a temporary or permanent
ban.

#### 3. Temporary Ban

**Community Impact**: A serious violation of community standards, including
sustained inappropriate behavior.

**Consequence**: A temporary ban from any sort of interaction or public
communication with the community for a specified period of time. No public or
private interaction with the people involved, including unsolicited interaction
with those enforcing the Code of Conduct, is allowed during this period.
Violating these terms may lead to a permanent ban.

#### 4. Permanent Ban

**Community Impact**: Demonstrating a pattern of violation of community
standards, including sustained inappropriate behavior, harassment of an
individual, or aggression toward or disparagement of classes of individuals.

**Consequence**: A permanent ban from any sort of public interaction within the
community.

### Attribution

This Code of Conduct is adapted from the [Contributor Covenant][homepage],
version 2.1, available at
[https://www.contributor-covenant.org/version/2/1/code_of_conduct.html][v2.1].

Community Impact Guidelines were inspired by
[Mozilla's code of conduct enforcement ladder][Mozilla CoC].

For answers to common questions about this code of conduct, see the FAQ at
[https://www.contributor-covenant.org/faq][FAQ]. Translations are available at
[https://www.contributor-covenant.org/translations][translations].

[homepage]: https://www.contributor-covenant.org
[v2.1]: https://www.contributor-covenant.org/version/2/1/code_of_conduct.html
[Mozilla CoC]: https://github.com/mozilla/diversity
[FAQ]: https://www.contributor-covenant.org/faq
[translations]: https://www.contributor-covenant.org/translations
