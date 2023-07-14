pipeline {
    agent any 
    environment {
        DEPLOY_TO = "production"

    }
    stages {
        stage (" when condition") {
            when {
              expression {
                BRANCH_NAME ==~ /(production|stagging)/

              }
            }

            steps {
                echo "deploying in production "
            }
        }
        stage ('second stage') {
            steps {
                echo " excute all"
            }
        }
    }

}
