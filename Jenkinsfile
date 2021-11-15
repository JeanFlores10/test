pipeline {
    agent any
    stages {
        stage("build"){
            steps{
                echo 'building the application'
                sh 'echo URL_TEST = $env.URL_FED/270-jenkinsfile-scripted-secret-text/' 
                sh 'echo URL_DEV = $URL_GIT/here/url'
                sh 'echo BUILD_NUMBER = $BUILD_NUMBER'
                echo 'asdsadasdasasdasdasdasd'
            }
        }

        stage("test"){
            steps{
                echo 'testing the application'
            }
        }

        stage("deploy"){
            steps{
                echo 'deplying the application'
            }
        }

    }
}
