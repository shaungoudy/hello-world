pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        echo 'test done'
      }
    }
    stage('') {
      steps {
        mail(subject: 'Test', body: 'Test jenkins', from: 'shaun.goudy@gmail.com', replyTo: 'shaun.goudy@gmail.com', to: 'shaun.goudy@gmail.com')
      }
    }
  }
}