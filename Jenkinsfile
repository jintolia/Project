pipeline {
    agent {label 'master'}
    stages {
        stage('Clone Git Repo') {
            steps {
                git credentialsId: '068c48ae-000d-41bd-8d60-e3e7a7297b89', url: 'https://github.com/jintolia/Project.git'
            }
        }        
    }
}
