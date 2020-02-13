pipeline {
    agent any
	tools { 
        maven 'Maven' 
        jdk 'Java' 
    }
    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                sh '''
                    echo "PATH = ${PATH}"
                    echo "M2_HOME = ${M2_HOME}"
                '''
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}