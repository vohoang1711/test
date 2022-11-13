pipeline {
    agent any
    stages {
        stage ('Build') {
            steps {
                // sh 'scp root@192.168.56.101:/var/lib/jenkins/workspace/Build-jar/target/spring-petclinic-2.7.3.jar /root'
                // sh 'java -jar spring-petclinic-2.7.3.jar'
                sh 'cd /var'
                sh 'touch test.tx'
            }
        }
    }
}
