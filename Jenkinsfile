pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                bat 'python sources\\test_calc.py' 
            }
        }
        stage('Deploy') {
            steps {
                echo '项目部署' 
            }
        }
    }
}