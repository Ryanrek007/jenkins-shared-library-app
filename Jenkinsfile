@Library("jenkins-shared-library@main")_

pipeline{
    agent any
    stages{
        stage("Hello World from Jenkins shared library"){
            steps{
                echo "Using jenkins Shared library"
                script{
                    hello.world()
                }
            }

        }
    }
}