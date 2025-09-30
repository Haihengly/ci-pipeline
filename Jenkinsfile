// @Library(['sharedLib@main', 'share-pipeline']) _ 

// def config = [ 
//     BUILD_DIR: 'Dev-Prod', 
//     envName: 'prod', 
//     version: '1.0.2', 
//     branch: 'main', 
//     REPO_URL: 'https://github.com/Haihengly/Products-Jenkins', 
//     build: true, 
//     deploy: true, 
// ] 

// pipelineStage(config)


@Library(['sharedLib@main', 'share-pipeline']) _ 

def config = [
    FOLDER: 'Dev-Prod',
    envName: env.BRANCH_NAME, 
    version: '1.0.2', 
    branch: env.BRANCH_NAME, 
    REPO_URL: 'https://github.com/Haihengly/Products-Jenkins', 
    build: true, 
    deploy: true, 
] 

pipelineStage(config)
