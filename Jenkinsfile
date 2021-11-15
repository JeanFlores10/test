pipeline {
    agent any

    environment {
        URL_TEST1 = "${env.URL_TEST}"
    }
    stages {
        stage("build"){
            steps{
                echo 'building the application'
                echo "URL_TEST = ${URL_TEST}";
                echo "URL_TEST = ${URL_TEST1}";
                echo "BUILD_NUMBEr = ${env.BUILD_NUMBER}";
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
