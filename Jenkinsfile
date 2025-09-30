@Library(['sharedLib@main', 'share-pipeline']) _ 

def config = [ 
    BUILD_DIR: 'Multibranch-Testing', 
    envName: 'dev', 
    version: '1.0.1', 
    branch: env.BRANCH_NAME, 
    REPO_URL: 'https://github.com/Haihengly/Dev-Service', 
    build: true, 
    deploy: true, 
] 

pipelineStage(config)