pipeline {	 
	agent any	 
    	stages {     	 
    	stage("Compile") {          	 
            	steps {               	 
                	sh "mvn clean package"          	 
            	}     	 
        	}     	 
    	stage("Unit test") {          	 
        	steps {               	 
                	sh "mvn test"          	 
            	}     	 
        	}	 
    	}
}

