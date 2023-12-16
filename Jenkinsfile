pipeline{
    agent any

    stages {
        stage(build){
            steps{
                bat "echo 'This is build phase'"
            }
        }
        stage(test){
            steps{
                bat "echo 'This is test phase'"
            }
        }
        stage(deploy){
            steps{
                bat "echo 'This is Deploy phase'"
            }
        }
    }
    
}