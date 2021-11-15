import hudson.model.*
import hudson.EnvVars
import groovy.json.JsonSlurperClassic
import groovy.json.JsonBuilder
import groovy.json.JsonOutput
import java.net.URL
import java.net.URLEncoder

pipeline {
    agent any

    stages {
        stage("build"){
            steps{
                echo 'building the application'
                echo "URL_TEST = ${URL_TEST}";
                echo "BUILD_NUMBEr = ${env.BUILD_NUMBER}";
            }
        }

        stage("test"){
            steps{
                echo 'testing the application'
                echo "URL_TEST = ${URL_TEST}";
            }
        }

        stage("deploy"){
            steps{
                echo 'deplying the application'
                echo "URL_TEST = ${URL_TEST}";
            }
        }

    }
}
