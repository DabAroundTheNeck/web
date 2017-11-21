pipeline {
  agent any
  stages {
    stage('Frontend') {
      steps {
        git(url: 'https://github.com/DabAroundTheNeck/web.git', branch: 'master')
        sh 'ls'
        sh 'cp index.html /var/www/html/web'
      }
    }
  }
}