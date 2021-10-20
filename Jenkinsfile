// SCRIPTED

//DECLARATIVE
pipeline {
     agent any
	 //agent { docker { image 'node:13.8'} }	 
	 stages {
	     stage ('Build') {
		   steps {
	         //sh 'node --version'
	         echo "Build"
			 echo "PATH - $env.PATH"
			 echo "BUILD_NUMBER - $env.BUILD_NUMBER"
			 echo "BUILD_ID - $env.BUILD_ID"
			 echo "JOB_NAME - $env.JOB_NAME"
			 echo "BUILD_TAG - $env.BUILD_TAG"
			 echo "UID_URL - $env.BUILD_URL"
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