# SINGLETON SD - DOCKER - TEMPLATES - ANGULAR

This project contains docker images templates for angular projects.

> The **main repository** is hosted in [gitlab.com/singletonsd/docker/templates/common](https://gitlab.com/singletonsd/docker/templates/angular.git) but it is automaticaly mirrored to [github.com/singletonsd](https://github.com/singletonsd/docker-templates-angular.git), [github.com/patoperpetua](https://github.com/patoperpetua/docker-templates-angular.git) and to [gitlab.com/patoperpetua](https://gitlab.com/patoperpetua/docker-templates-angular.git). If you are in the Github page it may occur that is not updated to the last version.

## AVAILABLE IMAGES

<!-- TODO: describe each image. -->
It can be downloaded by:
<!-- TODO: generate download urls.-->
```bash
curl -o bash_common.sh -L https://singletonsd.gitlab.io/scripts/common/latest/bash_common.sh && \
curl -o bash_script_test.sh -L https://singletonsd.gitlab.io/scripts/common/latest/bash_script_test.sh
```

## DOWNLOAD
<!-- TODO: -->
All scripts are available also inside a zip file under [this url](https://singletonsd.gitlab.io/docker/templates/angular/latest/images.zip). Or you can execute the following to download:

```bash
curl -o images.zip -L https://singletonsd.gitlab.io/docker/templates/angular/latest/images.zip && \
cd unzip images.zip && rm scripts.zip
```

## GIT HOOK

<!-- TODO: -->
You can setup shellcheck to be run before a commit. To do that just execute the following script under your git repository:

```bash
curl -s https://singletonsd.gitlab.io/scripts/common/latest/bash_script_test_hook_installer.sh | bash /dev/stdin
```

## STRUCTURE

Master branch is setup as latest folder. To use an specific version, put the version name before the file name like:

```url
https://singletonsd.gitlab.io/docker/templates/angular/latest/${IMAGE_NAME}
https://singletonsd.gitlab.io/docker/templates/angular/develop/bash_script_test_standalone.sh
https://singletonsd.gitlab.io/docker/templates/angular/v0.0.2/${IMAGE_NAME}
```

## DOCUMENTATION

<!-- TODO: -->

## TODO

- [ ] Fix documentation.
- [ ] Add script to test docker images.
- [ ] Zip all files and put inside pages.

----------------------

© [Singleton SD](http://www.singletonsd.com), Italy, 2019.
