pipeline {
    agent any
    stages {
        stage ('first stage'){
            environment {
                Github_creds = credentials('github_creds')
            } 
            steps {
                echo "github credentials are ${Github_creds}"
                echo "username is : ${Github_creds_USR}"
                echo "username is : ${Github_creds_psw}"

            }
        }
        stage ('second stage'){
            steps {
                echo "this is comming from second stage "

            }
        }
    }

}
