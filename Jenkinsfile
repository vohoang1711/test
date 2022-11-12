pipeline {
    agent any
    stages {
        stage ('Deploy') {
            steps {
                sh 'cd  spring-petclinic'
                sh './mvnw package'
                sh 'java -jar target/*.jar'
            }
        }
    }
}
