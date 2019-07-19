pipeline {
    agent { label 'Master' }
    stages {
        stage('build') {
            steps {
                echo "HI"
                sh "hostname"
                sh "uptime"
                sh "ls -l"
                sh "touch file1"
                sh "ls -l"
            }
         stage('build1') {
             steps {
                 echo "this is 2nd stage"
             }    
        }
    }
}
