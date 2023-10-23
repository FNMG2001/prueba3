pipeline {
    agent any
    stages {
        stage('Build'){
            steps{
                sh "docker build -t fnmg/pokedex-flask:${env.BUILD_NUMBER} ."
            }
        } 
    }
}
