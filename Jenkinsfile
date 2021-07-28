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
                echo 'Testing'
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
