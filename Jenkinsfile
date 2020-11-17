node{
   stage('SCM Checkout'){
     git 'https://github.com/Vishnu0659/pipeline'
   }
   stage('Compile-Package'){
      // Get maven home path   
      sh 'mvn package'
   }
   stage('Email Notification'){
      mail bcc: '', body: '''Hi Welcome to jenkins email alerts
      Thanks
      Vishnu''', cc: '', from: '', replyTo: '', subject: 'Jenkins Job', to: 'vishnu559vardhan@gmail.com'
   }
   
}
