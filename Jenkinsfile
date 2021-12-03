pipeline {
  agent any
  stages {
  stage('build & test')
    {
      steps
      {
        sh 'docker-compose run -d docker-compose.override.yml'
      }
      
    }
  }
  
}
