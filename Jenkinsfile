pipeline {
    agent any
    tools {
        maven "M3"
    }
    stages {
        stage('Build') {
            steps {
                git 'https://github.com/mini-boo/jenkins-test'
                sh "mvn clean package"
            }

        }
    }
}
