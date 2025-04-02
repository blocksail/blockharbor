# blockharbor
A comprehensive monorepo hosting production-grade Helm charts and resources for deploying highly optimized blockchain-related infrastructure on Kubernetes.

## Directory structure

The repository is organized as follows:

* `docker/`: Contains Docker images for various blockchain nodes and related services.
  * `docker/<image-name>/`: Each subdirectory contains the `Dockerfile` and necessary files for building the Docker image.
* `helm/`: Contains Helm charts for deploying blockchain nodes and infrastructure on Kubernetes.
  * `helm/<chart-name>/`: Each subdirectory contains the necessary files for the Helm chart, such as `Chart.yaml`, `values.yaml`, and templates.
* `terraform/`: Contains Terraform resources for defining and provisioning the infrastructure required for deploying blockchain nodes and related services.
* `docs/`: Contains additional documentation and resources.
* `CONTRIBUTING.md`: Guidelines for contributing to the project.
* `LICENSE`: Information about the project's license.
* `README.md`: Overview of the project and its goals.

## Quick guide to get started

To get started with the BlockHarbor project, follow these steps:

* Clone the repository to your local machine.
* Navigate to the `docker/` directory and build the Docker images for the blockchain nodes and related services.
* Navigate to the `helm/` directory and install the Helm charts for deploying the blockchain nodes and infrastructure on Kubernetes.
* Navigate to the `terraform/` directory and use Terraform to provision the required infrastructure.
* Refer to the `docs/` directory for additional documentation, guides, and resources.

For more detailed instructions, please refer to the specific documentation within each directory and the CONTRIBUTING.md file for guidelines on how to contribute to the project.
