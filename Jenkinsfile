pipeline{
    agent any 
    stages{
        stage('Greeting'){
            steps{
                echo 'Hello Everyone'
            }
        }
        stage('Hostname'){
            steps{
                sh "hostname"
            }
        }
        stage('Files'){
            steps{
                sh "ls -lah"
            }
        }
        stage('Make Directory'){
            steps{
                sh "mkdir TestFile1"
            }
        }
        stage ('Check new dir'){
            steps{
                sh "ls "
            }
        }
        stage ('Cleaning Up'){
            steps{
                sh "rm -R TestFile1"
            }
        }
    }
}