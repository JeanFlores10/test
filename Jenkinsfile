
def fullname = null
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

                fullname = getURL()

                echo "${fullname}"
               
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

def getURL(){
    echo "my name is ${env.NAME_KEYS} and my lastname is ${env.LASTNAME}"
}
