pipeline {
    agent any
    
    stages {
        stage('Build') { 
            steps {
                withMaven('mvn') {
                    sh 'mvn -B -DskipTests clean package' 
                }
            }
        }
    }
}