pipeline{
  agent any
  stages{
    stage('clone'){
      steps{
        git branch:'main',url:'https://github.com/Sridharpeddamanishi9710/CalculatorProg.git';
      }
    }
    stage('compile'){
      steps{
        sh 'javac Calculator.java'
      }
    }
      stage('build'){
        steps{
          sh 'java Calculator 25 5'
        }
      }
      stage('test'){
        steps{
          sh 'java Calculator 40 -10'
        }
      }
      stage('Deploy'){
        steps{
          echo 'Deployment completed'
        }
      }
    }
}
