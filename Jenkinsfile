pipeline {
  agent {
    label 'Java11'
  }
  stages {
    stage('Build and Deploy') {
      steps {
        echo 'Copying html files to Tomcat'
        sh 'sudo cp -u  ~/builds/workspace/UtilityChargesCalculatorUI_main/*.html /opt/tomcat/webapps/utilityAppUi/'
      }
    }

  }
}