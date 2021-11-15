pipeline {
    agent any
    stages {
        stage("build"){
            steps{
                echo 'building the application'
                echo "URL_TEST = ${env.URL_TEST}";
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
