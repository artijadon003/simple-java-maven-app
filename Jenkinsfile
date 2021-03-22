node{
    stage('SCM Checkout'){
      git 'https://github.com/artijadon003/simple-java-maven-app.git'
    }
    stage('Compile-Package'){
        //Get maven home path
        def mvnHome = tool name: 'M3', type: 'maven'
        sh "${mvnHome}/bin/mvn clean install"
    }
}
