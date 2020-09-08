pipeline {
    agent any 
    stages {
        stage('Stage 1') {
            steps {
                echo 'Rocket Chat' 
            }
        }
    }
    post {
        success {
            rocketSend 'Sucess!'
        }
        failure {
            rocketSend 'Build Failed!'
        }
    }
}
