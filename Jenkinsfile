pipeline {

  agent { label 'permanent_node' }

  stages {
    stage('Build') {
      steps {
        sh '/bin/mvn -B -DskipTests clean package'
      }
    }
  }

}
