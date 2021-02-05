pipeline {
    agent {label 'MASTER'}
    stages {
        stage('Source'){
            steps {
                git 'https://github.com/ankit3297/kuchbhi.git'
            }
        }
        stage('Package'){
            steps {
                sh 'mvn package'
            }
        }
    }
}