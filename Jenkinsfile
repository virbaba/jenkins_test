pipeline {
    agent any

    stages {  // <-- All stages should be inside this block
        stage("Install Dependencies") {
            steps {
                sh 'npm install'
            }
        }

        stage('Run Tests') {  
            steps {
                sh 'npm test'
            }
        }
    }
}
