# IITM TDS - Graded Assignment 2, Question 9

## Objective
Create and push a Docker image to Docker Hub with the specifically assigned tag: `24f2008471`.

## Important Note
Since local Docker execution is restricted or not feasible in the provided assignment environment, this repository utilizes **GitHub Actions** to automatically build and push the Docker image directly to Docker Hub. 



## How to Deploy (Automated Workflow)

To replicate this automated build and push process:

1. **Push the Code:** Ensure this repository is pushed to your GitHub account (`amanvx/tds-ga2-q9`).
2. **Configure GitHub Secrets:** Navigate to **Settings** -> **Secrets and variables** -> **Actions** in your GitHub repository and add the following *Repository secrets*:
   * `DOCKER_USERNAME`: Your Docker Hub username (e.g., `amanvx`).
   * `DOCKER_PASSWORD`: Your Docker Hub Access Token (highly recommended) or password.
3. **Trigger the Workflow:**
   * Go to the **Actions** tab in your repository.
   * Select the workflow (e.g., `Docker Image CI`).
   * Click **Run workflow** to start the build and push process.

## Result

Once the GitHub Actions workflow successfully completes, the Docker image will be compiled, tagged with `24f2008471`, and pushed to the remote registry.

The published image can be verified at the following URL:
`https://hub.docker.com/repository/docker/amanvx/tds-ga2-q9/general`
