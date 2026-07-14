#GitHub Actions:
------------------- 
#step1 

paymentAction
│
├── src
├── pom.xml
├── Dockerfile
├── README.md
└── .github
      └── workflows

#create dir
mkdir -p .github/workflows

#GitHub Action
.github/workflows/build.yml

#git operation
git add .
git commit -m "Added GitHub Action"
git push origin main

# check git Action in Browser

# Deployment to cloud

#GitHub Secrets
Settings → Secrets and variables → Actions

DOCKER_USERNAME=cnsnoida
DOCKER_PASSWORD=xxxxxx

EC2_HOST=54.xx.xx.xx
EC2_USER=ec2-user

EC2_SSH_KEY= .pem file
