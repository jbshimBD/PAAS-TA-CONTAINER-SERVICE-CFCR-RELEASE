# Cloud Foundry Container Runtime
A [BOSH](http://bosh.io/) release for [Kubernetes](http://kubernetes.io).  Formerly named **kubo**.

- **Slack**: #cfcr on https://slack.cloudfoundry.org
- **Pivotal Tracker**: https://www.pivotaltracker.com/n/projects/2093412
- **The original CFCR readme file**: https://github.com/cloudfoundry-incubator/kubo-release/tree/v0.34.0


<!-- vscode-markdown-toc-config
	numbering=true
	autoSave=true
	/vscode-markdown-toc-config -->
<!-- /vscode-markdown-toc -->

## <a name='UsagePaasta'></a>Usage for PaaS-TA Container Service

For applying release to PaaS-TA Container Service, please create release by apply the version and syncronize with that service configuration.
This is a customized kubo-release version for PaaS-TA Container Service Project based on kubo-release(ver 0.34.0).

`bosh create-release --force --tarball ./releases/kubo-release-0.34.1.tgz --name kubo --version 0.34.1`
