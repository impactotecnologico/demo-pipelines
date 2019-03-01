pipeline {
    agent any
    stages {
    	stage('init') {
    		steps {
    			echo 'Hola mundo'
    		}
    	}
		stage('build') {
        	steps {
				javac -d . src/net/impactotecnologico/HolaMundo.java
			}
        }
        stage('finish') {
        	steps {
        		echo 'Done'
        	}
        }
    }
}

