# My First Step Of Github-Actions! 🚀

<img width="861" alt="10" src="https://github.com/moshdev2213/actions/assets/103739510/c9ade06f-0653-4785-b46e-a53d27abd34f">

## Greeting Workflow 💬🌟

🚀 I've implemented a GitHub Actions workflow that automatically posts cheerful greeting messages on every new issue and pull request! 🎈 This enhances contributor engagement and communication within our repository. Custom scripts ensure that comments are added for all events, making interactions more lively and welcoming. Let's keep the community spirit high! 💬🌟

### Build And Publish Workflow 🐳 

Additionally, this repository includes a powerful GitHub Actions workflow that automates the build and publishing process to Docker Hub whenever changes are pushed to the `master` branch 🐳 .

### Workflow Details

#### Greeting Workflow

The greeting workflow:
- Responds to new issues and pull requests with personalized greetings.
- Enhances community engagement through automated interactions.

#### Build And Publish Workflow

The build and publish workflow performs the following steps:
- Checks out the code from the repository.
- Sets up Node.js environment based on the specified version.
- Installs npm dependencies using `npm ci`.
- Builds the project with `npm run build` if the build script is present.
- Builds and pushes a Docker image to Docker Hub using the `mr-smithers-excellent/docker-build-push@v6` action.

### Workflow Triggers

Both workflows trigger on:
- Push to the `master` branch.
- Pull requests targeting the `master` branch.

### Node.js Version

The build and publish workflow is configured to run with Node.js version `18.x`.

For more information about GitHub Actions and automating builds and tests with Node.js, please refer to the [GitHub Actions documentation](https://docs.github.com/en/actions/automating-builds-and-tests/building-and-testing-nodejs).

