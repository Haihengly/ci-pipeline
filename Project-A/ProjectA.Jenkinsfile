@Library(['sharedLib@main', 'pipeline-library']) _ 

def config = [
    FOLDER: 'Dev-Prod',
    envName: env.BRANCH_NAME, 
    version: '1.0.2', 
    branch: env.BRANCH_NAME, 
    REPO_URL: 'https://github.com/Haihengly/Testing-Project-A', 
    build: true, 
    deploy: true, 
] 

pipelineStage(config)
