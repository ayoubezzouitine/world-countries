    
   node {
    stage('git stage'){
      git 'https://github.com/ayoubezzouitine/world-countries'
    }
    stages {
        stage('Build') {
            steps {
                sh 'mvn -B'
            }
        }
    }
}
