@Library(“shared-lib@master”)_

pipeline {
    agent any
    stages {
	stage('Code Checkout'){
	 steps {
	  script {
	    def workingDir = checkoutCode("https://github.com/cnu4235/HPEIND.git","main")
	    echo $workingDir
	  }
	 }
	}
    }
}
