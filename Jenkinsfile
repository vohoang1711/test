pipeline {
    agent any
    stages {
        stage ('Build') {
            steps {
                sh 'scp root@192.168.56.101:/var/lib/jenkins/workspace/Build-jar/target/spring-petclinic-2.7.3.jar /var/lib/jenkins/workspace/test'
                sh 'java -jar spring-petclinic-2.7.3.jar'
            }
        }
    }
}
