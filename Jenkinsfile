pipeline {
    agent any
	triggers {
		cron 15 19 * * *
			}
    stages {
        stage('Build') {
            steps {
                echo 'Hello World'
            }
        }
		
		stage('Test') {
            steps {
                echo 'Hello World'
            }
        }
		stage('Deploy') {
            steps {
                echo 'Hello World'
            }
        }
    }
    post { 
        always { 
            echo 'I will always say Hello again!'
        }
    }
}


