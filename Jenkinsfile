node {
    stage('SCM Checkout') {
        git "https://github.com/johnvarkas1/demoApp"
    }
    stage('Compile-Package') { 
        sh 'mvn -f demo/pom.xml clean package'
    }
}
