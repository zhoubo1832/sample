
pipeline {
  agent any
  stages {
    stage('init') {
      steps {
        echo "init..."
      }
    }
    
    stage('checkout') {
      steps {
        echo "checkout..."
      }
    }
  
  }

  post {
    always {
      echo "post..."
    }
  }
}
