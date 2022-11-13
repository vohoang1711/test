pipeline {
    agent any
    stages {
        stage ('Build') {
            steps {
                sh 'scp /var/lib/jenkins/workspace/Build-jar/target/spring-petclinic-2.7.3.jar root@192.168.56.103:/root'
            }
        }
    }
}
