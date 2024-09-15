pipeline {
  agent any
          
	tools {
		maven "Maven"
	}
  stages {
	    stage('Scm Checkout') {
		    steps {
			    	checkout scm
		    }
	    }
  
	    stage('print') {
		    steps {
			    	echo "hello"
		    }
	    }
  }
}
