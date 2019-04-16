pipeline {

  agent any

  stages {
    stage('Build') {
      steps {
        sh '/bin/mvn -B -DskipTests clean package'
      }
    }
  }

}
