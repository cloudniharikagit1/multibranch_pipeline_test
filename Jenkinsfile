pipeline {
    agent any
    environment {
        name = "pinky"
        course = "devops"
    }
    stages {
        stage ('first stage'){
            environment {
                course = "k8s"
            }
            steps {
                echo "this is comming from first stage ${name} "
                echo "this is comming from ${course} first stage "

            }
        }
        stage ('second stage'){
            steps {
                echo "this is comming from ${course} second stage "
                sh "printenv"
                
            }
        }
    }

}
