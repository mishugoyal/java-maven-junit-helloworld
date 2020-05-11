
stage('install'){

    sh '/appl/app/apache-maven-3.3.9/bin/mvn -B -V -U -e clean install'
    echo "Succcessfully install"
}

stage('test'){
    sh '/appl/app/apache-maven-3.3.9/bin/mvn -B -V -U -e clean test'
    echo "Succcessfully test"
}

  
