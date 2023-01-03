@Library("jenkins-shared-library@dev")_

pipeline{
    agent any
    stages{
        stage("Hello World from Jenkins shared library"){
            steps{
                echo "Using jenkins Shared library"
                echo "on dev branch"
                script{
                    hello.world()
                }
            }

        }
    }
}