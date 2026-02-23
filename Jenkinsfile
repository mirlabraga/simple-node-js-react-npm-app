pipeline {
    agent any

    tools {
        tools {nodejs "nodejs"}
    }

    stages {
        stage('Build') {
            steps {
                sh 'npm install'
            }
        }
    }
}
