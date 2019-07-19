pipeline {
    agent { label 'Master' }
    stages {
        stage('build') {
            steps {
                echo "HI"
                sh "hostname"
                sh "uptime"
            }
        }
    }
}
