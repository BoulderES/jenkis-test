pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
		sh '''
			bash -c "echo 'test'"
		'''
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}

