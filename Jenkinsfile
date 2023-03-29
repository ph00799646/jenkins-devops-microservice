pipeline {
	agent any
	stages {
		stage('Build' ) {
          steps {
			 echo  "Build"
		  }
		}
		stage('Test' ) {
			steps {
			 echo  "Test"
		  }
		}
		stage('Deploy' ) {
			steps {
			 echo  "Deploy"
		  }
		}
	}
	
	post {
		always {
			echo  "Build completed"
		}
		success {
			echo  "Build Success"
		}
		failure {
			echo  "Build failure"
		}
	}
}
