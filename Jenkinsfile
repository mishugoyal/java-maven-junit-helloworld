pipeline {
    agent any
    stages {
        stage('init') {
            steps {
                step([$class: 'WsCleanup'])
                script {
                    echo 'hello'
                    sh '/appl/app/apache-maven-3.3.9/bin/mvn -B -V -U -e clean install'
                }
            }
        }
    }
}
  
