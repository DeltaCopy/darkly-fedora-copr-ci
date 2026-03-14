  # darkly-fedora-copr-ci
  RPM build spec for building Darkly on the Fedora COPR.

  All build specs credits go to @hazel-bunny (https://github.com/hazel-bunny)

  This auto triggers Fedora Copr builds: <https://copr.fedorainfracloud.org/coprs/deltacopy/darkly/builds>

  Upstream: https://github.com/Bali10050/Darkly

  ## Active releases available

  - Fedora 42
  - Fedora 43
  - Fedora rawhide

  # Instructions

  Enable the COPR repository then install the package.

  <pre>
  sudo dnf copr enable deltacopy/darkly
  sudo dnf in darkly
  </pre>

  #### GitHub Actions scheduled build status

  [![Darkly Fedora COPR build CI](https://github.com/DeltaCopy/darkly-fedora-copr-ci/actions/workflows/darkly-fedora-copr-ci.yml/badge.svg)](https://github.com/DeltaCopy/darkly-fedora-copr-ci/actions/workflows/darkly-fedora-copr-ci.yml)

  #### Fedora Copr last build status

  [![Copr build status](https://copr.fedorainfracloud.org/coprs/deltacopy/darkly/package/darkly/status_image/last_build.png)](https://copr.fedorainfracloud.org/coprs/deltacopy/darkly/package/darkly/)

  ## Latest version
  v0.5.35
