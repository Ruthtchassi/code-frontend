pipeline {
    agent any
    //bon
    stages {
        stage('Build') {
            steps {
              sh '/usr/share/maven/bin/mvn clean compile'
              //  ./mvnw 'clean compile' 
            }
        }
        stage('Test') {
            steps {
              // sh '/usr/share/maven/bin/mvn clean verify'
          //      ./mvnw 'clean verify'
            }
        }
    }
}
