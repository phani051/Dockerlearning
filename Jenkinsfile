pipeline{
    agent any

    stages {
        stage(Hello1){
            steps{
                bat "echo hello"
            }
        }
        stage(sleep){
            steps{
                bat "PING 1.1.1.1 -n 1 -n 10 >NUL"
            }
        }
        stage(helllo2){
            steps{
                bat "echo hello2"
            }
        }
    }
    
}