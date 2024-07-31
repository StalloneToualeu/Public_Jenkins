pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
                git branch: 'main', credentialsId: 'StalloneToualeu', url: 'https://github.com/StalloneToualeu/Public_Jenkins'
            }
        }
    }
}

