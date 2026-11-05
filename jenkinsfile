pipeline {
    agent any
    stages {
        stage('Build and Archive') {
            steps {
                sh 'echo "This is our application artifact content" > app.txt'
                archiveArtifacts artifacts: 'app.txt', fingerprint: true
            }
        }
    }
}
                                                    

