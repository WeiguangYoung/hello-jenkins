pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building the application...'
                // 在这里替换为你实际的构建命令，比如：
                // sh 'mvn clean package'  // 对于 Maven 项目
                // sh 'npm install'       // 对于 Node.js 项目
                python main.py
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests...'
                // 在这里替换为你实际的测试命令
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying the application...'
                // 在这里替换为你实际的部署命令
            }
        }
    }
}
