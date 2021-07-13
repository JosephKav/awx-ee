# AWX EE
[![Docker Repository on Quay](https://quay.io/repository/josephkav/awx-ee/status "Docker Repository on Quay")](https://quay.io/repository/josephkav/awx-ee)

An Ansible Execution Environment for AWX project.

## Regenerating the build context with podman:

```bash
$ tox -epodman
```

## Regenerating the build context with docker:

```bash
$ tox -edocker
```