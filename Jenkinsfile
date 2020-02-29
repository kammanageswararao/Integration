pipeline {
    agent any
	    stages {
        stage('Build') {
            steps {
                echo 'Hello World'
		  echo "Git Commit is ->" %GIT_COMMIT%
	         echo "Git Commiter name is ->" %GIT_COMMITTER_NAME%
	         echo "Git AUTHOR name is ->" %GIT_AUTHOR_NAME%
			    
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


