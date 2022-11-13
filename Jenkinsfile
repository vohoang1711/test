pipeline {
    agent any
    stages {
        stage ('Build') {
            steps {
                sh 'scp /root/spring-petclinic-2.7.3.jar root@192.168.56.103:/root'
            }
        }
    }
}
