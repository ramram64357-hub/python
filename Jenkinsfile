pipeline{
    agent any
stages{
    stage('github'){
        steps{
            git credentialsId: 'ramzz_file', url: 'https://github.com/ramram64357-hub/python.git'
        }
    }
    stage('test'){
        steps{
            sh'jenkins --version'

        }
    }
    stage('deploy'){
        steps{
            sh'java --version'
            sh'python3 app.py'
        }
    }
}
}
