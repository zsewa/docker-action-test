# docker-action-test
This repository demonstrates a github action that builds a Docker image and makes it available using the packages function. It also creates a release with the image exported to a tar file.

## How to trigger the github action
The actions runs when a new tag is created.
```sh
git tag v0.1.0
git push origin v0.1.0
```

## Notes
Remember to give read and write permission to the workflow. This option is located in the `Settings` > `Actions` > `General` > `Workflow permissions` of the repository.
