def BuildVersion
pipeline {
    options {
        timeout(time: 30, unit: 'MINUTES')

    }
    environment {
        registry = "dockerhubuser/repo"
        registryCredential = 'dockerhub'
        dockerImage = ''
    }
    agent {
        label 'master'
    }
    stages {
        stage('Trigger appropriate CI job depending on changed config file'){

        }
    }
}

