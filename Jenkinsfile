
pipeline {
    agent any
    environment{
        NAME_KEYS = credentials('NAME_TEXT')
        LASTNAME = credentials('LAST_NAME')
    }
    stages {
        stage("build"){
            steps{
                script{
                def add = "Sayan";
                echo 'building the application'
                echo '================================'
               
                getURL(add);

                echo '================================'
                }
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

def getURL(address){
    
    echo "my name is ${NAME_KEYS} and my lastname is ${LASTNAME} and my direction is ${address}"
}
