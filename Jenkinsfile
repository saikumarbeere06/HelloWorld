pipeline {
    agent any
	stages {
	    stage("Build") {
		    when {
			    expression {
				    BRANCH_NAME == 'main'
			    }
		    }
	      steps {
		      echo "Building the application"
		      sh "echo $BRANCH_NAME"
	      }
	    }
	    stage("Test") {
	      steps {
		      echo "Testing the application"
	      }
	    }
	    stage("Deploy") {
	      steps {
		      echo "Deploying the application"
	      }
	    }
	}
}
	
	        
	
	
			  
