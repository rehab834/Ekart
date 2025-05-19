pipeline {
    agent any
    tools {
        jdk 'jdk 8'
        maven 'maven 3'
    }


    stages {
 
        stage('Compile') {
            steps {
                sh "mvn compile"
            }
        }
        stage('Test') {
            steps {
                sh "mvn test"
            }
        }
        stage('Package') {
            steps {
                sh "mvn package"
            }
        }
    }
}
