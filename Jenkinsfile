pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
		echo "Did you know that the system's java version is the following? "
		sh 'java -version'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
		sh 'uname -a'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
		sh 'ls -la'
		sh 'ip a'
            }
        }
    }
}
