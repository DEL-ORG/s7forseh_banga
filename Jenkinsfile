pipeline {

    agent any


options {
  buildDiscarder logRotator(artifactDaysToKeepStr: '', artifactNumToKeepStr: '', daysToKeepStr: '3', numToKeepStr: '3')
  disableConcurrentBuilds()
  timeout(time: 1, unit: 'HOURS')
  timestamps()
  retry(1)
}



    stages {


        stage('test') {
            steps {
                sh  '''
                ls
                uname -r
                touch gwen2
                '''
            }
        }

        stage('validate') {
            steps {
                sh  '''
                ls
                '''
            }
        }

       stage('scanned') {
            steps {
                sh  '''
                ls
                '''
            }
        }

        stage('build') {
            steps {
                sh  '''
                ls
                '''
            }
        }

        stage('push') {
            steps {
                sh  '''
                ls
                '''
            }
        }

        stage('deploy') {
            steps {
                sh  '''
                ls
                '''
            }
        }                

    }


}
