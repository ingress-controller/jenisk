pipeline {
    agent jnlp-slave
    stages {
        stage('YELL') {
            steps {
                sh 'echo "HELLO WORLD"'
                sh '''
                    chmod 755 ./kus.sh
                    ./kus.sh
                    echo "KUSSS"
                '''
            }
        }
    }
}
