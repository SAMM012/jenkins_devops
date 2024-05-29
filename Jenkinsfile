pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Building...'
                // Aquí puedes agregar los comandos necesarios para compilar tu proyecto
            }
        }
        stage('Test') {
            steps {
                echo 'Testing...'
                // Aquí puedes agregar los comandos necesarios para ejecutar las pruebas
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying...'
                // Aquí puedes agregar los comandos necesarios para desplegar tu aplicación
            }
        }
    }
    post {
        success {
            echo 'Pipeline completed successfully!'
        }
        failure {
            echo 'Pipeline failed!'
        }
    }
}
