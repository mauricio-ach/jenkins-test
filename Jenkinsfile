pipeline {
    agent any  // Ejecutar en cualquier agente disponible

    stages {
        stage('Build') {
            steps {
                sh 'echo "console.log(\'Construyendo el proyecto...\')"'
            }
        }

        stage('Test') {
            steps {
                sh 'echo "console.log(\'Ejecutando pruebas...\')"'
            }
        }

        stage('Deploy') {
            steps {
                sh 'echo "console.log(\'Desplegando el proyecto...\')"'
            }
        }
    }
}
