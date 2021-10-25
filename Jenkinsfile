pipeline {
	agent any
	//agent { docker { image 'python:3.7.2' } }
 	stages {
 		stage("Compile") {
 			steps {
 				echo " need to build python code"
 			}
 		}
 		stage("Unit test") {
 			steps {
 				sh "python tests.py"
 			}
 		}
 	}
}
