pipeline {
    agent any
    tools {
        maven 'MAVEN_HOME'  // This must match your Maven installation name in Jenkins Global Tools
    }
    stages {
        stage('Build') {
            steps {
                bat 'mvn clean install'
            }
        }
    }
}
