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
                echo 'Tested'
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
