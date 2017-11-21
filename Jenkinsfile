pipeline {
  agent any
  stages {
    stage('Frontend') {
      steps {
        git(url: 'https://github.com/DabAroundTheNeck/web.git', branch: 'master')
        sh 'rm /var/www/html/web/* -r'
        sh 'mv -v ./* /var/www/html/web/'
      }
    }
  }
}