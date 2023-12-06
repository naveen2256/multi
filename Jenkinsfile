pipeline{
    agent any
    stages {
        stage('uat branch') {
            steps {
                sh 'echo "uat branch changes" '
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
