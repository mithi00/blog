pipeline {
    agent any

    stages {
        stage('Initialize') {
            steps {
                echo 'Initialized'
            }
        }
      stage('Test') {
            steps {
                echo 'Testedd'
            }
        }
      stage('Deploy') {
            steps {
                echo 'Deployed'
            }
        }
    }
    post{
      failure{
        echo 'Failure Occured'
      }
    }
}
