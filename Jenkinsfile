pipeline {
    agent {
        docker {
            image 'gradle:jdk8'
        }
    }
    stages {
        stage('Build') {
            steps {
                sh 'mvn clean package'
            }
        }
    }
}
