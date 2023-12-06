pipeline{
    agent any
    stages {
        stage('main branch') {
            steps {
                sh 'echo "main branch changes" '
            }
        }
        stage('test') {
            steps {
                sh 'echo "sprint1 applicaiton....." '
            }
        }
        stage('deploy application') {
            steps {
                sh 'echo "deploying application........" '
            }
        }
    }
}
