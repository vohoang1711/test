pipeline {
    agent any
    stages {
        stage ('Build') {
            steps {
                sh 'su jenkins -s /bin/bash'
                sh 'scp spring-petclinic-2.7.3.jar root@192.168.56.103:/root'
            }
        }
    }
}
