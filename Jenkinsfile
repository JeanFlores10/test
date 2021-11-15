pipeline {
    agent any
    stages {
        stage("build"){
            steps{
                withCredentials([string(credentialsId:'NAME_TEXT', variable: 'NAME_SECRET')]){
                    echo "NAME = ${env.NAME_TEXT}"
                }

                echo 'building the application'
                echo '================================'
                
                echo "BUILD_NUMBER = ${env.BUILD_NUMBER}"
                
                echo "URL_GIT = ${env.GIT_URL}"
                
                echo "NAME = ${env.NAME_TEXT}"
                
                echo "LAST_NAME = ${env.LAST_NAME}"
                echo '================================'
               
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

