// SCRIPTED

//DECLARATIVE
pipeline {
     // agent any
	 agent { docker { image 'node:13.8'} }	 
	 stages {
	     stage ('Build') {
		   steps {
	         sh 'node --version'
	         echo "Build"
	 	}
   }
   stage ('Test') {
		   steps {
	 echo "Build"
	 	}
   }
   stage ('Intergration Test') {
		   steps {
	 echo "Build"
	 	}
   }
  }
  post {
     always { 
	     echo 'Im awesome. I run always'
		 }
	 success { 
	     echo 'I run when you are successful'
		 }
	 failure { 
	     echo 'I run when you fail'
		 }
	 }
}