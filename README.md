# Introduction
This is a proof of concept for how to use Git (specifically, git + GitHub) workflows as a way of submitting, reviewing, selecting, and approving funding requests for the No Starch Press Foundation.

# Workflow
1. Users fork the repo and copy the template from request-template.yaml into their own file.
2. Users fill in the fields, save, commit, and push their code back up to their forked repo. They then submit a pull request.
3. NSPF reviewers assign the PR for review, and discuss it using comments.
4. Once all reviewers have had a chance to discuss, they vote on whether to approve or decline the request.
5. If the request is approved, the reviewers accept the pull request and the YAML is merged into the repo.

# Why GitHub?
* _GitHub is widely used in the hacker community._
* _Pull requests work for more than just code._ GitHub has a built-in system for reviewing and approving new contributions to a common base of knowledge. Normally, this is code, but it works reasonably well for text.
* _It's easy to track status._ Your number of outstanding funding requests is the number of open PRs. You can see when a funding request was approved by looking at the git log. When your funding request is approved (or denied), you get a notification through your GitHub account.
* _It's transparent._ If you want to see examples of prior approved requests, just look at the master branch of the repo. Because it's a public repo, anybody can submit a pull request. Everybody can see which pull requests were approved or denied by doing a search. And because it's YAML, the data is both machine-parseable (allowing you to do analysis) and human-readable.
