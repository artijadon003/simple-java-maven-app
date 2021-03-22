node{
    stage('SCM Checkout'){
        git 'https://github.com/artijadon003/simple-java-maven-app.git'
    }
    stage('Compile-Package'){
        sh 'mvn clean install'
    }
}
