# Darkly-Fedora

All build specs credits go to @hazel-bunny (https://github.com/hazel-bunny)

This auto triggers Fedora Copr builds: <https://copr.fedorainfracloud.org/coprs/deltacopy/darkly/builds>

Builds from src: https://github.com/Bali10050/Darkly

GitHub actions workflow, uses the packager.py script from https://github.com/DeltaCopy/darkly-packager and auto generates a build spec file.

A COPR build is then invoked remotely using the copr-cli <https://developer.fedoraproject.org/deployment/copr/copr-cli.html>

#### Fedora Copr last build status

[![Copr build status](https://copr.fedorainfracloud.org/coprs/deltacopy/darkly/package/darkly/status_image/last_build.png)](https://copr.fedorainfracloud.org/coprs/deltacopy/darkly/package/darkly/)
