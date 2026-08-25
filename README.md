  # darkly-fedora-copr-ci
  RPM build spec for building Darkly on the Fedora COPR.

  All build specs credits go to @hazel-bunny (https://github.com/hazel-bunny)

  This auto triggers Fedora Copr builds: <https://copr.fedorainfracloud.org/coprs/deltacopy/darkly/builds>

  Upstream: https://github.com/Bali10050/Darkly

  # Instructions

  Enable the COPR repository then install the package.

  <pre>
  sudo dnf copr enable deltacopy/darkly
  sudo dnf in darkly
  </pre>

  ## Package structure

  The overall package is now split into 2 dependencies darkly-qt6 and darkly-qt5

  Installing  provides darkly6.so and darkly5.so respectively.

  The .spec file can be found at https://github.com/DeltaCopy/darkly-fedora-copr-ci/blob/main/.github/darkly.spec.template

  #### GitHub Actions scheduled build status

  [![Darkly Fedora COPR build CI](https://github.com/DeltaCopy/darkly-fedora-copr-ci/actions/workflows/darkly-fedora-copr-ci.yml/badge.svg)](https://github.com/DeltaCopy/darkly-fedora-copr-ci/actions/workflows/darkly-fedora-copr-ci.yml)

  #### Fedora Copr last build status

  [![Copr build status](https://copr.fedorainfracloud.org/coprs/deltacopy/darkly/package/darkly/status_image/last_build.png)](https://copr.fedorainfracloud.org/coprs/deltacopy/darkly/package/darkly/)

  ## Latest version
  <a href="https://github.com/Bali10050/Darkly/releases">
    <img src="https://img.shields.io/badge/darkly-v0.5.39-orange" alt="darkly-v0.5.39">
  </a>
