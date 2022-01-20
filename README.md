# Gatsby GitHub Deployment Script
Bash script that automatically builds and deploys a static Gatsby site to GitHub Pages.

## How do I use it?
1. Move all of your code to a new directory called `code` inside the root directory (root should be empty)
2. Copy the `deploy.sh` script to the code directory
3. Run the script using `./deploy.sh`

## Assumptions
These are the default values present in the script, feel free to change any of these to suit your needs.
1. Your release branch is called `main` (this is the branch that GitHub Pages is deployed from)
2. Your latest changes live in a branch called `develop`

##### PS: Make sure the script is executable by running `chmod +x deploy.sh` if you're not able to run it
