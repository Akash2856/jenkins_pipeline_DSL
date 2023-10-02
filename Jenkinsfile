pipeline {
    agent any
    stages {
        stage('SCM') {
            steps {
                echo "git pull my code"
		git 'https://github.com/Akash2856/maven.git'
            }
        }
        stage('Deploy') {
            steps {
                echo "deploying the code"
            }
        }
        stage('Test') {
            steps {
                echo "test my final webapp"
            }
        }
    }
}
