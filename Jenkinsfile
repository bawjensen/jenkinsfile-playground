pipeline {
    agent { label 'mac' }

    stages {
        stage('build') {
            steps {
                echo 'hello there 1'
                script {
                    sleep(1)
                    error('testing')
                }
                echo 'hello there 2'
            }
        }
    }
}
