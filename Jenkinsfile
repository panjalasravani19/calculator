pipeline{
  agent any
  stages{
    stage('clone'){
      steps{
        git branch:'main',url:'https://github.com/panjalasravani19/calculator.git';
      }
    }
    stage('compile'){
      steps{
        sh 'javac calculator.java'
      }
    }
      stage('build'){
        steps{
          sh 'calculator 25 5'
        }
      }
      stage('test'){
        steps{
          sh 'java calculator 40 -10'
        }
      }
      stage('Deploy'){
        steps{
          echo 'Deployment completed'
        }
      }
    }
}
