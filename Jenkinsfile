pipeline {
    agent any
    stages {
        stage ('Build') {
            steps {
                sh 'scp -r spring-petclinic root@192.168.56.103:/root'
            }
        }
    }
}
