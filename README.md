# ghcr-test
Testing docker build to github container registry

Github Action patterned after [publishing-a-package-using-an-action]( https://docs.github.com/en/packages/managing-github-packages-using-github-actions-workflows/publishing-and-installing-a-package-with-github-actions#publishing-a-package-using-an-action)

Builds and pushes a new docker container on release using the release tag.

The container built can be run like so:
```
docker run -it ghcr.io/johnbradley/ghcr-test:1.0.1
```
