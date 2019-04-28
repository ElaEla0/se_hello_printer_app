pipeline {
    agent any
    stages {
        stage('Deps') {
            steps {
	            sh 'make deps'
        	}
        }
	stage('Linter')
	stage('Test') {
	    steps {
			sh 'make test'
		}

    	}
  }
}
