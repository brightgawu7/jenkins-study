pipeline{
    agent any

    environment{
        DEMO='1.3'
    }
    
    stages{
        stage('One'){
            steps {
                echo "Hello Bright Edem $DEMO "
                
                bat "docker images"
            }
        }
    }
    
}