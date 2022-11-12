pipeline {
    agent any
    stages {
        stage ('Deploy') {
            steps {
                sh 'cd /root/spring-petclinic'
                sh './mvnw package'
                sh 'java -jar target/*.jar'
            }
        }
    }
}
