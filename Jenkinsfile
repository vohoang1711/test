pipeline {
    agent any
    stages {
        stage ('Build') {
            steps {
                sh 'scp hello.txt root@192.168.56.103:/root'
            }
        }
    }
}
