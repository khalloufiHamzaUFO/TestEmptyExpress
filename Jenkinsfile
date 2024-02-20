pipeline {
     agent any     

    stages {
        stage('Installing...') {
            steps {
                sh 'npm install '
            }
        }
         
        stage('Building...') {
            steps {
                sh 'npm run start'
            }
        }
    }
}
