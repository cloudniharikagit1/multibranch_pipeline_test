pipeline {
    agent any
    environment {
        name = "pinky"
        course = "devops"
    }
    stages {
        stage ('first stage'){
            steps {
                echo "this is comming from first stage ${name} "
            }
        }
        stage ('second stage'){
            steps {
                echo "this is comming from ${course} second stage "
            }
        }
    }

}
