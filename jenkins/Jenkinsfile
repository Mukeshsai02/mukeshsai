pipeline {
   agent any
  

   tools {
      // Install the Maven version configured as "M3" and add it to the path.
	  jdk 'Java8'
      maven "Maven 3.9.3"
   }
   
   stages
   {
   stage('checkout') {
         steps {
            // Get some code from a GitHub repository
            git 'https://github.com/saimtej/saimtej.git'
        }
         }
	}
}
