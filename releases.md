# Tekton CLI Releases

## Release Frequency

Tekton CLI follows the Tekton community [release policy][release-policy]
as follows:

- Versions are numbered according to semantic versioning: `vX.Y.Z`
- A new release is produced on a monthly basis
- Four releases a year are chosen for [long term support (LTS)](https://github.com/tektoncd/community/blob/main/releases.md#support-policy).
  All remaining releases are supported for approximately 1 month (until the next
  release is produced)
    - LTS releases take place in January, April, July and October every year
    - The first Tekton CLI LTS release will be **v0.30.0** in January 2023
    - Releases happen towards the middle of the month, but the exact date may vary,
      depending on week-ends and readiness

Tekton CLI produces nightly builds, publicly available on
`gcr.io/tekton-nightly`. 

### Transition Process

Before release v0.28 Tekton CLI has worked on the basis of an undocumented
support period of four months, which will be maintained for the releases between
v0.26 and v0.27.

## Release Process

Read about releasing the Tekton CLI in the [release process documentation]
[tekton-release-process].

Further documentation available:

- [Tekton resources][tekton-releases-docs]
- Standard for [release notes][release-notes-standards]

## Releases

### v0.29

- **Latest Release**: [v0.29.0][v0-29-0] (2022-01-05) ([docs][v0-29-0-docs])
- **Initial Release**: [v0.29.0][v0-29-0] (2022-01-05)
- **End of Life**: 2023-02-04
- **Patch Releases**: [v0.29.0][v0-29-0]

### v0.28

- **Latest Release**: [v0.28.0][v0-28-0] (2022-11-25) ([docs][v0-28-0-docs])
- **Initial Release**: [v0.28.0][v0-28-0] (2022-11-25)
- **End of Life**: 2023-01-24
- **Patch Releases**: [v0.28.0][v0-28-0]

### v0.27

- **Latest Release**: [v0.27.0][v0-27-0] (2022-10-11) ([docs][v0-27-0-docs])
- **Initial Release**: [v0.27.0][v0-27-0] (2022-10-11)
- **End of Life**: 2023-02-10
- **Patch Releases**: [v0.27.0][v0-27-0]

### v0.26

- **Latest Release**: [v0.26.0][v0-26-0] (2022-09-02) ([docs][v0-26-0-docs])
- **Initial Release**: [v0.26.0][v0-26-0] (2022-09-02)
- **End of Life**: 2023-01-08
- **Patch Releases**: [v0.26.0][v0-26-0]

### v0.25

- **Latest Release**: [v0.25.0][v0-25-0] (2022-07-22) ([docs][v0-25-0-docs])
- **Initial Release**: [v0.25.0][v0-25-0] (2022-07-22)
- **End of Life**: 2022-11-21
- **Patch Releases**: [v0.25.0][v0-25-0]

## End of Life Releases

Older releases are EOL and available on [GitHub][tekton-cli-releases].


[release-policy]: https://github.com/tektoncd/community/blob/main/releases.md
[tekton-chains]: https://github.com/tektoncd/chains
[tekton-cli-releases]: https://github.com/tektoncd/cli/releases
[tekton-releases-docs]: tekton/README.md
[release-notes-standards]:
    https://github.com/tektoncd/community/blob/main/standards.md#release-notes
[tekton-release-process]: RELEASE_PROCESS.md

[v0-29-0]: https://github.com/tektoncd/cli/releases/tag/v0.29.0
[v0-28-0]: https://github.com/tektoncd/cli/releases/tag/v0.28.0
[v0-27-0]: https://github.com/tektoncd/cli/releases/tag/v0.27.0
[v0-26-0]: https://github.com/tektoncd/cli/releases/tag/v0.26.0
[v0-25-0]: https://github.com/tektoncd/cli/releases/tag/v0.25.0

[v0-29-0-docs]: https://github.com/tektoncd/cli/tree/v0.29.0/docs
[v0-28-0-docs]: https://github.com/tektoncd/cli/tree/v0.28.0/docs
[v0-27-0-docs]: https://github.com/tektoncd/cli/tree/v0.27.0/docs
[v0-26-0-docs]: https://github.com/tektoncd/cli/tree/v0.26.0/docs
[v0-25-0-docs]: https://github.com/tektoncd/cli/tree/v0.25.0/docs
