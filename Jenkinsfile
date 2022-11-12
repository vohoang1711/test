pipeline {
    agent any
    tools {
        //gradle 'Gradle-7.4'
        maven 'Maven'
    stages {
        stage ('Deploy') {
            steps {
                sh 'mvn package'
            }
        }
    }
}
