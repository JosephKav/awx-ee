# AWX EE
[![Docker Repository on Quay](https://quay.io/repository/josephkav/awx-ee/status "Docker Repository on Quay")](https://quay.io/repository/josephkav/awx-ee)

The default Execution Environment for AWX.

## Build the image locally

First, [install ansible-builder](https://ansible-builder.readthedocs.io/en/stable/installation/).

Then run the following command from the root of this repo:

```bash
$ ansible-builder build -v3 -t quay.io/ansible/awx-ee # --container-runtime=docker # Is podman by default
```
