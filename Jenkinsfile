pipeline {
    agent any 
    tools { 
        maven 'MAVEN_HOME' 
    }
    stages {
        stage('clean') { 
            steps {
                sh "mvn clean"
            }
        }
        stage('Test') { 
            steps {
                sh "mvn clean"
            }
        }
        stage('Deploy') { 
            steps {
                sh "mvn package"
            }
        }
    }
}
