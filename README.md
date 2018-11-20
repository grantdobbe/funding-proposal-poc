# Introduction
This is a proof of concept for how to use Git (specifically, git + GitHub) workflows as a way of submitting, reviewing, selecting, and approving funding requests for the No Starch Press Foundation.

# Workflow
1. Users fork the repo and copy the template from request-template.yaml into their own file.
2. Users fill in the fields, save, commit, and push their code back up to their forked repo. They then submit a pull request.
3. NSPF reviewers assign the PR for review, and discuss it using comments.
4. Once all reviewers have had a chance to discuss, they vote on whether to approve or decline the request.
5. If the request is approved, the reviewers accept the pull request and the YAML is merged into the repo.
