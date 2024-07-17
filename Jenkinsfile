pipeline {
    //agent any
    agent { node { label 'workstation1' } }

    stages {
        stage('Code') {
            steps {
                echo 'Hello world'
                error 'This is an error'
            }
        }

    }
}
