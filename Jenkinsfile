node{
   stage('SCM Checkout'){
     git 'https://github.com/Vishnu0659/pipeline'
   }
   stage('Compile-Package'){
      // Get maven home path  
      def mvnHome=tool name: 'Maven latest', type: 'maven'
      sh "${mvnHome}/bin/mvn package"
   }
   
}
