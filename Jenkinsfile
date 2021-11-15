pipeline {
    agent any
    environment{
        NAME_KEYS = credentials('NAME_TEXT')
    }
    stages {
        stage("build"){
            steps{


                echo 'building the application'
                echo '================================'
                
                "${NAME_KEYS}"
               
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

