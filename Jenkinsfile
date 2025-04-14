pipeline{
    agent any
    // enviornment{
    //     //Credentials Here
    // }
    stages{
        stage('clone code'){
            steps{
                checkout scm
            }
        }
        stages("installing Dependency"){
            steps{
                sh 'npm install'
                sh 'node app.js'
            }
        }

    }
}