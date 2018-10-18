
pipeline {
    agent any

    stages {
        stage('grant permission') {
            steps {
                sh 'chmod 755 pipeline.sh'
            }
        }
        stage('execute') {
            steps {
                echo './pipeline.sh'
            }
        }
      }
    }
}
