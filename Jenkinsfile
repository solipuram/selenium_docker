pipleine {
    agent {label 'chromium-slave'}
    
    stages {
        stage('build')
        {
          steps {
              sh '''
                mvn clean install
                ls -lrth
                
              '''
          }
        }
    }
}
