pipeline {
    agent { label 'mac' }

    stages {
        stage('build') {
            steps {
                echo 'hello there 1'
                script {
                    Random random = new Random()
                    sleep(random.nextInt(10))
                }
                echo 'hello there 2'
            }
        }
    }
}
