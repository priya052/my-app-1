node{
   stage('SCM Checkout'){
      git 'https://github.com/priya052/my-app-1.git'
   }
   stage('Compile-Package'){
     def mvnhome = tool name: 'local maven', type: 'maven'  
     sh "\$(mvnhome)/bin/mvn package"
   }
}
