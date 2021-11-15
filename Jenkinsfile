pipeline {
    agent any
    stages {
        stage("build"){
            steps{
                echo 'building the application'
                echo "URL_TEST = ${env.URL_FED}/270-jenkinsfile-scripted-secret-text/" 
                echo "URL_DEV = ${env.URL_GIT}/here/url"
                echo "BUILD_NUMBER = ${env.BUILD_NUMBER}"
                echo "asdsadasdasasdasdasdasd"
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



def 