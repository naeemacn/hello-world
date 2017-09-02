pipeline {
  agent any
  stages {
    stage('Send Email') {
      steps {
        mail(subject: 'Testing JEnkins', body: 'We are testing email from BlueOcean', from: 'naeem@tuks,co.za', to: 'naeem@tuks.co.za', replyTo: 'naeem@tuks.co.za')
      }
    }
  }
}