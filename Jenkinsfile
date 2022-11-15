 pipeline{

    agent any
     
    stages{
        stage('git checkout'){
            steps{
                git branch: 'main', url: 'https://github.com/ahedtajouri/DevOpsProject1.git'
            }
        }
        stage('maven build'){
            steps{
                sh 'mvn clean install'
            }
        }
      
    }
 }
 