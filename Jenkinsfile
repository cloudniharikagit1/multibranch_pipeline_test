pipeline {
    agent any 
    environment {
        DEPLOY_TO = "production"

    }
    stages {
        stage (" when condition") {
            when {
                environment name: 'DEPLOY_TO' , value = 'production'
            }
            steps {
                echo "deploying in production "
            }
        }
    }

}
