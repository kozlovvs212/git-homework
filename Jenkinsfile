pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'go build -o main'  // Собирает бинарник с использованием Golang
            }
        }
        stage('Test') {
            steps {
                sh 'go test ./...'  // Запускает тесты для всех модулей
            }
        }
        stage('Deploy') {
            steps {
                sh 'scp main user@server:/path/to/deploy'  // Копирует собранный файл на сервер
                sh 'ssh user@server "systemctl restart app"'  // Перезапускает сервис
            }
        }
    }
}
