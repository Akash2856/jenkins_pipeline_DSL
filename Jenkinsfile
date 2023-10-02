pipeline {
    agent any
    stages {
        stage('SCM') {
            steps {
                echo "git pull my code"
		git 'https://github.com/Akash2856/maven.git'
            }
        }
        stage('Build') {
            steps {
                sh 'mvn clean package'
            }
        }
        stage('Test') {
            steps {
                echo "test my final webapp"
            }
        }
    }
}
