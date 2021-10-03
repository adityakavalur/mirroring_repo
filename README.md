## Mirroring repo

This repository mirrors Source repo on GitHub to Target repo on GitLab, through GitHub actions.

Mirroring logic: https://github.com/adityakavalur/github-gitlab-ci we are using only one of the 3 possible example workflows.

Source Repository: https://github.com/adityakavalur/source_repo.git defined in the GitHub Action file

Target Repository: https://gitlab.com/akavalur/target_repo.git defined in GitHub Action file

Source PAT: Defined in the Secret section of this repository

Target PAT: Defined in the Secret section of this repository

Do not add other users to this repo at a high enough permission level that they can view secrets.
