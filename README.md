# bcamp_data_platform_gcp
BCAMP and Applied Curiosity's Data Platform Infrastructure

## GCP Walking Skeleton

Building on our Azure and AWS infrastructure setup, I'm presenting you with a new challenge: configuring a similar system using Google Cloud Platform (GCP) with Pulumi. Here’s a roadmap to guide your exploration and documentation:

1. **Establish a New Git Repository:**
Create a separate repository for our GCP infrastructure to organize and manage our codebase efficiently.
2. **Install Pulumi and GCP SDK:**
Make sure Pulumi is ready and install the Google Cloud SDK. This tool is essential for managing GCP resources.
3. **Configure Google Cloud SDK:**
Set up the Google Cloud SDK with your GCP credentials. This includes initializing the SDK and configuring it to interact with your GCP account.
4. **Create a Pulumi Project for GCP:**
Initialize a new Pulumi project in the **`infra`** directory that’s tailored for GCP, focusing on the specifics of Google Cloud.
5. **Authenticate Pulumi with GCP:**
Pulumi will need to authenticate with GCP using a service account. Research how to create and manage these credentials securely, particularly in a CI/CD setup.
6. **Setup GitHub Actions for GCP Deployment:**
Develop a GitHub Actions workflow that automates the deployment of GCP resources. Adapt our existing workflows to align with GCP’s deployment strategies.
7. **Deploy a Basic GCP Resource:**
Start with a simple deployment, such as creating a Google Cloud Storage bucket or a Compute Engine instance. Document the Pulumi configurations and the steps involved.
8. **Detailed Documentation:**
For each step, provide a comprehensive description of the actions taken, the reasons behind each decision, and any obstacles encountered. Include relevant command-line inputs, code excerpts, and visual aids as necessary.
