pipeline {
    agent any
    stages {
        stage('YELL') {
            steps {
                sh 'echo "HELLO WORLD"'
                sh '''
                    ./kus.sh
                '''
            }
        }
    }
}
