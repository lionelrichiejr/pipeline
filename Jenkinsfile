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
        always {
            rocketSend channel: 'general', message: ''
        }
    }
}
