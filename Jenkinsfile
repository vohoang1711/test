pipeline {
    agent any
    stages {
        stage ('Deploy') {
            steps {
                cd '/root/spring-petclinic'
                sh './mvnw package'
                sh 'java -jar target/*.jar'
            }
        }
    }
}
