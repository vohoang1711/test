pipeline {
    agent any
    stages {
        stage ('Deploy') {
            steps {
                sh 'scp root@192.168.56.101:/var/lib/jenkins/workspace/Build-jar/target/spring-petclinic-2.7.3.jar root@192.168.56.104:/root'
                sh 'ssh root@192.168.56.104'
                
            }
        }
    }
}
