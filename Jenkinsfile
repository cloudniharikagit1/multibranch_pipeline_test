pipeline {
    agent any 
    environment {
        DEPLOY_TO = "production"
    }
    stages {
        stage (" when condition") {
            when {
                not {
                    equals expected: "productions" , actual: "${DEPLOY_TO}"
                }
            }
            steps {
                echo "deploying in production "
            }
        }
    }
}
