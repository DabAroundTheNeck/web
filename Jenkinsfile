pipeline {
  agent any
  stages {
    stage('Frontend') {
      steps {
        git(url: 'https://github.com/DabAroundTheNeck/web.git', branch: 'master')
        sh 'cd /var/www/html/web'
        sh 'git pull'
      }
    }
  }
}