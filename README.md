# svc-web-demo
This is a web demo service for presenting it right after infra installation.

## How does it work
1. Using [terraform](https://terraform.io) configuration to setup infrastucture needed for deployments in one of cloud providers: [DigitalOcean](https://digitalocean.com), [Azure](https://azure.microsoft.com/en-us/), [AWS](https://aws.amazon.com), [GCP](https://cloud.google.com)
2. Create a new repo based on this template.
3. Passing secrets during setup to repo, so it's aware about how to deploy and where to.
4. Run actions to make a deployment or create a pull request to make a PR deployment.



