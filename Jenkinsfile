pipeline {
  // This means that the script will run on your CI machine, and will use its environment as is.
  agent any
  stages {
    // Each stage gets a graphical representation on the blue ocean UI
    stage('Build') {
      steps {
            echo "Starting Build, triggered by $BRANCH_NAME";
            echo "Building ${env.BUILD_ID}";

      }
    }
    stage('Test') {
      steps {
        echo 'Starting tests'
        //sh './vendor/bin/psalm common';
      }
    }
  }
}
