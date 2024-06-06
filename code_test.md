

Code Test Job Description

Objective:

Deploy a Rust "Hello World" application using Docker in a Kubernetes cluster managed by Minikube. Optionally Integrate vulnerability scanning or autoscaling (not mandatory).

Requirements:

    Setup Minikube Cluster:
        Install and configure Minikube or an alternative to simulate an on-premise Kubernetes environment.

    Application Deployment:
        Containerize and deploy the into the Kubernetes cluster.

    Documentation:

        Provide a README.md with clear instructions on how to:

            Set up a local Kubernetes cluster (for example with Minikube).

            Build and deploy the application.

            Run the SonarQube scan or perform autoscaling.

    Autoscaling (optional):

        Implement autoscaling based on CPU utilization using Kubernetes capabilities.

        Document how to configure, test and observe autoscaling.

    Vulnerability Scanning with SonarQube (optional):

        Integrate a Github Action SonarQube to scan the Docker image for vulnerabilities as part of the deployment process.

        Document the setup and scanning process in the README.

Evaluation Criteria:

    Correctness: The application must be correctly deployable and accessible in a local docker environment.

    Security: The Docker image should be scanned for critical vulnerabilities as reported by SonarQube (optional).

    Code Quality: The DevOps code should be clean, well-organized, and maintainable.

    Documentation Quality: Documentation should clearly guide the setup, deployment, and scanning processes.

Submission Instructions:

    Provide a link to a GitHub repository containing all deployment scripts, Dockerfile(s), SonarQube configuration, and documentation.

    Ensure all scripts are executable and that the documentation is comprehensive and easy to follow.


