 pipeline{

    agent any
     
    stages{
        stage('git checkout'){
            steps{
                git branch: 'main', url: 'https://github.com/ahedtajouri/DevOpsProject1.git'
            }
        }
         stage{
        stage('unit testing'){
            steps{
               sh 'mvn test'
            }
        }
    }
 }
 }