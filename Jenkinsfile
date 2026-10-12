pipeline {
    agent any

    stages {
        stage('Recuperation du code source') {
            steps {
                checkout scm
            }
        }

        stage('Affichage de la date systeme') {
            steps {
                sh 'date'
            }
        }
    }
}
