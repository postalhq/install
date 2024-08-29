# Postal Installation Tools

This repository contains the tools needed to quickly get started with Postal.

For full details on how to use it [read the documentation](https://docs.postalserver.io).

## Installing pre-requisites

There are a number of pre-requisites needed to run Postal. These are detailed [in the documentation](https://docs.postalserver.io/getting-started/prerequisites). If you're feeling a bit lazy (or just doing a lot of testing) , we have a couple of scripts which you can use to install everything needed.

**Note:** these will install database services with insecure passwords so shouldn't be used as-if for production environments.

For Postal v2 you can use the following:

```bash
curl https://raw.githubusercontent.com/postalserver/install/main/prerequisites/install-ubuntu.v2.sh | bash
```

For Postal v3 you can use the following:

```bash
curl https://raw.githubusercontent.com/postalserver/install/main/prerequisites/install-ubuntu.v3.sh | bash
```
