# Auto Git Deployer

Auto Git Deployer is a user-friendly web application that simplifies the process of cloning and deploying.

## Overview

This Streamlit-based application allows users to:

1. Clone GitHub repositories directly from a web interface
2. Deploy both Python and JavaScript projects
3. Automatically install project dependencies
4. Generate public URLs for deployed applications using ngrok

## Key Features

- Support for Python and JavaScript projects
- Automatic dependency management
- ngrok integration for easy sharing
- Example repositories for quick testing

## How It Works

1. Users select or input a GitHub repository URL
2. The app clones the repository
3. Users select the main file to run
4. The app installs dependencies and starts the server
5. A public ngrok URL is generated for accessing the deployed application

Auto Git Deployer streamlines the process of going from a GitHub repository to a publicly accessible web application, making it easier for developers to showcase their projects or quickly deploy prototypes.

## Quick Start

To get started with Auto Git Deployer, follow these steps:

1. Install Poetry (if not already installed):pip install poetry
2. Set up the project:poetry install
3. Activate the Poetry shell:poetry shell
4.  Run the Streamlit app:streamlit run app.py
   
This will start the Auto Git Deployer application, and you can access it through your web browser.
