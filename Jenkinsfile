pipeline {
    agent any

    tools {
        maven 'MyMaven'
    }

    stages {

        stage('Checkout') {
            steps {
                git 'https://github.com/<vikas-1421>/MyMavenSeleniumApp1.git'
            }
        }

        stage('Build') {
            steps {
                sh 'mvn clean test'
            }
        }
    }
}
