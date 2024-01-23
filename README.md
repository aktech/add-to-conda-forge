# Add PyPi package to conda-forge

[![Add to conda-forge](https://github.com/aktech/add-to-conda-forge/actions/workflows/add-to-conda-forge.yml/badge.svg)](https://github.com/aktech/add-to-conda-forge/actions/workflows/add-to-conda-forge.yml)

A GitHub Actions interface to add package to conda-forge by generating a recipe with `grayskull` and creating a pull request in [conda-forge/staged-recipes](https://github.com/conda-forge/staged-recipes),
everything entirely using workflow dispatch.

## Usage

- Fork the repo
- Run the workflow via workflow dispatch.

<img width="1902" alt="workflow-dispatch" src="https://github.com/aktech/add-to-conda-forge/assets/5647941/64c14de9-53f9-41f6-8de9-c0f7039bf94f">

After the workflow is ran successfully, there should be a PR in [conda-forge/staged-recipes](https://github.com/conda-forge/staged-recipes) 🚀:

<img width="1267" alt="Screenshot 2023-12-07 at 10 48 36 am" src="https://github.com/aktech/add-to-conda-forge/assets/5647941/507d6f82-27e5-4893-8f92-6a0b43dc4571">
