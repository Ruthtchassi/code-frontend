pipeline {
    agent any
    //bon
    stages {
        stage('Build') {
            steps {
              // sh "'$mvnHome/bin/mvn' clean compile"
                ./mvnw 'clean compile' 
            }
        }
        stage('Test') {
            steps {
              // sh "'$mvnHome/bin/mvn' clean verify"
                ./mvnw 'clean verify'
            }
        }
    }
}
