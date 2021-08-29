# devops-genin

A DevOps challenge that will grant you the title Genin (Starter).

Challenges:

1. Breaking down a story to tasks
2. Docker
3. CI/CD

## The Story

You're doing your day-to-day work; suddenly, a new challenge has been presented to you. You read the instructions in the JIRA ticket and then reach out to the developer who forged the challenge.

(Challenge #2) A developer tells you that he created the application [docker-cats](https://github.com/unfor19/docker-cats) and asked for your help with improving the [Dockerfile](https://docs.docker.com/engine/reference/builder/).

(Challenge #3) You ask your team leader about this challenge, and he tells you that you should also add a [CI/CD](https://docs.github.com/en/actions/guides/about-continuous-integration) process that builds the application and pushes it to [DockerHub](https://hub.docker.com/).

## General Guidelines

- Committing secrets/passwords/private data to your Git repository will expose your ninja identity (auto-disqualify).
- (Challenge #1) Break down the story into tasks and write down the "definition of done" per task (something measurable). Feel free to share the output if you want to be 100% sure you're on the right track.
- (Challenge #3) The CI/CD logic is up to you (push, pull-request, etc.). The naming convention for tagging Docker images is also up to you. Follow best practices and make sure that it makes sense.
- Everything is legitimate; feel free to use any available resource you can find; that includes asking friends for help, as long as you take responsibility for every single line of code.


## Technical Instructions

1. Since you can't edit the GitHub repository [docker-cats](https://github.com/unfor19/docker-cats), navigate to the repository's page and click the Use This Template button (There's **NO NEED** to tick `Include all branches`).
1. Set the repository's privacy to **private**; I want you to feel comfortable that none is watching your masterpiece until you're done.
1. Create a `SOLUTION.md` file and add it to the generated GitHub repository. This file should contain documentation of the whole process.
1. Document what you did, why you did it, during this adventure. This part is crucial, and to be even more specific - this whole challenge means nothing if you can't reproduce your work and explain the logic behind your actions.
1. Use [GitHub Actions](https://github.com/features/actions) as the CI/CD service. You can only use this specific service because it's excellent for beginners and fun for experts.
1. Register for [DockerHub](https://hub.docker.com/), if you haven't already, to host your published Docker images.

## Upon Completing The Challenge You Are ...

- Familiar with Git and Docker
- Learned how to create a CI/CD process with hands-on experience
- Realized how important it is to document your work

## Authors

Created and maintained by [Meir Gabay](https://github.com/unfor19)

## License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/unfor19/devops-genin/blob/master/LICENSE) file for details
