pipeline {
    agent any

    stages {
        stage ("list files"){
            step {
                sh '''
                ls -lrt
                cd src
                ls -lrt
                '''
            }

        }


    }


}