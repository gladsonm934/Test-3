pipeline{
  agent any
  stages{
    stage('Checkout Code'){
      steps{
        git 'https://github.com/gladsonm934/Test-3'
      }
    }
    stage('Build'){
      steps{
        sh 'echo "Building the app"'
      }
    }
    stage('Test'){
      steps{
        sh 'echo "Running Test"'
      }
    }
    stage('Deploy'){
      steps{
        sh 'echo "Deploying"'
      }
    }
  }
}
