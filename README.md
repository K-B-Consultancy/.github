# K.B Consultancy shared GitHub config

Public on purpose: every client repository reads `.github/release-drafter.yml` from here through Release Drafter's `_extends: .github`, and a public repository needs no extra token. It holds only release-note categories and labels. No code, no secrets, no client data.

This repository is the single owner of that config. Change it here, in a pull request; the next release in every repository picks it up.
