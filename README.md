# Bytex Network

**Bytex** is a decentralized blockchain network built from scratch to support a fair and transparent distribution model based on computational contribution. The network is designed to be lightweight, efficient, and community-driven.

## Founder

This project was founded by **Radhwan Majdoub** (`radoinmajdoub@gmail.com`). It is now being donated to a non-profit foundation for open-source development and adoption.

## Features

- SHA-256-based mining algorithm  
- 50 million BTX max supply  
- 10% allocation for the founder via the Genesis Block  
- 10% allocation for the non-profit foundation via the Genesis Block  
- Fully decentralized node-based network  
- Dynamic block rewards every 10 minutes  
- Open-source and community-driven

## Getting Started

To initialize and push the full Bytex blockchain to GitHub:

```bash
# Set up Git user credentials
git config --global user.name "Radhwan Majdoub"
git config --global user.email "radoinmajdoub@gmail.com"

# Unzip the Bytex project
unzip BytexNetwork.zip
cd BytexNetwork

# Initialize a new Git repository
git init

# Add the remote GitHub repository
git remote add origin https://github.com/radhwan/bytex-network.git

# Add all project files
git add .

# Commit the files
git commit -m "Initial commit of Bytex blockchain by Radhwan Majdoub"

# Push the code to the main branch
git branch -M main
git push -u origin main