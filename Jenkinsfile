pipeline {
    agent any

    tools {
        maven 'maven-3.6.0'
        jdk 'jdk-8'
    }

    stages {
        stage('Build') {
            steps {
               sh 'mvn -B -DskipTests clean package'
            }
        }
    }
}
