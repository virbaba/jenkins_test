// This is groovi script
pipeline{
    agent any


    stages {
        stage("Install Dependencies")
        steps {
            sh 'npm install'
        }
    }

    stage('Run Tests'){
        steps {
            sh 'npm test'
        }
    }
}