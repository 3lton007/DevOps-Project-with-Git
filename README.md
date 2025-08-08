# DevOps-Project-with-Git

Elevate Labs DevOps Internship Task 4

## Implementation
- Inititalized DevOps Project-with-Git Repository. Cloned the repo to local using git clone, and made changes to README.
- Used Simple node.js application and pushed it to main branch.
- Created seperate dev and feature branch using "git checkout -b dev" and also initiating upstream to track local and remote changes. 
- created .gitignorefile and pushed sample CI/CD changes to feature branch and pushed it to feature branch.
- Initiated a pull request from /feature branch to /dev and merged the pull request. Updated Dev branch locally using "git pull" and again intiated pull request for main branch. 
- Created Tags for V1.0.0 Application Feature Release. 
- Added Documentation in V1.0.1 Release.


## Technologies Used
- **CI/CD**: GitHub Actions
- **App**: Node.js
- **Containerization**: Docker

## Getting Started

### Prerequisites
- Docker 20.0+
- Node.js 16+


### Installation
```bash
# Clone repository
git clone https://github.com/3lton007/DevOps-Project-with-Git
cd DevOps-Project-with-Git

# Install dependencies
npm install

# Build Docker image
docker build -t devops-app .
