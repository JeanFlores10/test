
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
               
                getURL()

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
    
    def name = "${NAME_KEYS}"
    echo "my name is ${name}"
}
