pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                sh '''
                python3 click.py
				python3 NewScreen.py
                '''
            }
        }
    }
}
