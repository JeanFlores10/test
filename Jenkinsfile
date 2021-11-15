pipeline {
    agent any
    environment{
        NAME_KEYS = credentials('NAME_TEXT')
    }
    stages {
        stage("build"){
            steps{
                withCredentials([string(credentialsId:'NAME_TEXT', variable: 'NAME_SECRET')]){
                    sh ('echo ${env.NAME_SECRET}')
                    sh ('echo ${NAME_SECRET}')
                }

                echo 'building the application'
                echo '================================'
                
                sh ('echo ${NAME_KEYS}')
               
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

