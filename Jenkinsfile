pipeline{
    agent any

    environment{
        DEMO='1.3'
    }
    
    stages{
        stage('One'){
            steps {
                echo "Hello Bright Edem $DEMO "
                
                sh '''
                    echo "Using a multi-line shell step"
                    chmod +x text.sh
                    ./text.sh
                '''
            }
        }
    }
    
}