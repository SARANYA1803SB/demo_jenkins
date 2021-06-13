pipeline {
    agent any
     tools {
        jdk 'JDK11'
    }
    stages {
        stage('build') {
            steps {
			echo 'Build started'
                sh 'mvn --version'
	        sh 'mvn clean compile'
	        sh 'mvn test'
	        echo 'Build finished Succesfully'
            }
        }
    }
}
