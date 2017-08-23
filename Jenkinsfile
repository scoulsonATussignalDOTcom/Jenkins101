pipeline {
    agent { docker 'php' }
    stages {
        stage('build') {
            steps {
                sh 'php --version'
				sh 'echo "Hello world"'
				sh '''
					echo "Multiline shell steps works too"
					ls -lah
				'''
            }
        }
    }
}