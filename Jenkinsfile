pipeline {
    agent any
	stages {
	    stage("Build") {
	      steps {
		      if (env.BRANCH_NAME=="main") {
		      echo "Building the application"
		      }
		      else if (env.BRANCH_NAME=="dev") {
			      echo " Building the appication in dev environment"
			       }
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
	
	        
	
	
			  
