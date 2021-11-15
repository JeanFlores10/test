pipeline {
    agent any
    stages {
        stage("build"){
            steps{
                echo 'building the application'
                echo '================================'
                
                echo "BUILD_NUMBER = ${env.BUILD_NUMBER}"
                
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

