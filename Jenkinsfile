pipeline {
    agent any
    environment{
        NAME_KEYS = credentials('NAME_TEXT')
        LASTNAME = credentials('LAST_NAME')
    }
    stages {
        stage("build"){
            steps{


                echo 'building the application'
                echo '================================'

                echo "my name is ${NAME_KEYS} and my lastname is ${LASTNAME}"
               
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

