pipeline {
   agent any 
   tools {
    maven 'maven3'
   }
   stage('SCM Checkout'){
	   steps{
     git 'https://github.com/javahometech/my-app'
	   }
   }
   stage('Maven Build'){
	   steps {
            sh 'mvn clean package'
	}
   }
}
