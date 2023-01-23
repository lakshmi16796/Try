pipeline {
  agent any
  stages {
	  

    stage ("Edit")
    {
      steps {
        
        script {
	 		       
		
	def printParams() {
 		 env.getEnvironment().each { name, value -> println "Name: $name -> Value $value" }
	}
	printParams()
	}  
    }
  }
   }
  }



