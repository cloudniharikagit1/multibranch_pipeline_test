pipeline {
    agent any 
    environment {
        DEPLOY_TO = "production"

    }
    stages {
        stage (" when condition") {
            when {
              allOf {
                branch 'production'
                environment name: 'DEPLOY_TO', value: 'production'
              }
            }

            steps {
                echo " all satisfied "
            }
        }
        stage ('second stage') {
            steps {
                echo " excute all"
            }
        }
    }

}
