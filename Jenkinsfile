pipeline {
    agent any
    stages {
        stage('Build') { 
            steps {
                withMaven(maven : 'apache-maven-3.6.9') {
                bat'mvn clean compile'
            }
        }
    }
}
