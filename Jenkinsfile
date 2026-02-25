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
        sh 'java calculator.java'
      }
    }
    stage('build'){
      steps{
        sh 'java calculator.java'
      }
    }
    stage('test'){
      steps{
        sh 'java calculator.java'
      }
    }
    stage('deploy'){
      steps{
        sh 'java calculator.java'
      }
    }
  }
}
        
          
