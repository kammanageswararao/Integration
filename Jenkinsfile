pipeline {
    agent any
	    stages {
        stage('Build') {
            steps {
		    step{
                echo 'Hello World'
		  
	         echo "Git Commiter name is ->"  %GIT_COMMITTER_NAME%
			 } 
	         
			      
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


