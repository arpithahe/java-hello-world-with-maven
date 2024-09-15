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
  	    stage('Build') {
		    steps {
			    sh 'mvn clean'
		    }
	    }
           stage('Test') {
		    steps {
			    echo "Testing..."
			    sh 'mvn test'
		    }
	    }		
	    
  }
}
