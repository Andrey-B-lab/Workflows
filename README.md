# This repo contains different scenario workflows files examples

- **version-workflow.yml** - every time someone tags a version, GitHub Action creating the docker image and push it to EKS and ECR.
- **CiPullRequest.yml** - every time we open pull request from the branch with name syntax patch/ ot feature/ ,GitHub Action builds Docker Image and run Snyk and Sonar Cloud scans.
- **TLApproveMerge.yml** - once the Pull Requst approved, GitHub Action building the Docker Image, creating tag, scan it and pushes to ECR.

-------------------------
