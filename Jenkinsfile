pipeline {
    agent { docker { image 'maven:3.3.3' } }
    stages {
        stage('build') {
           steps {
                sh 'ls && pwd'
                sh 'mvn -B -DskipTests clean package' 
            }
        }
    }
}
