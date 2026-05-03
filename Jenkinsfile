	pipeline {
	    agent any
	    stages {
	        stage('Checkout') {
	            steps {
	                git 'https://github.com/Cocolilo1979/cocop2a'
	            }
	        }
	        stage('Build') {
	            steps {
	                // simple example (no maven project)
	                sh 'echo "Building project..."'
	            }
	        }
	        stage('Test') {
	            steps {
	                sh 'echo "Running tests..."'
	            }
	        }
	        stage('Deploy') {
	            steps {
	                sh 'echo "Deploying application..."'
	            }
	        }
	    }
}
