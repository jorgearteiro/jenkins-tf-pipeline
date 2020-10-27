pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                sh 'echo lz.tf' 
                sh 'git add .'
                sh 'git commit -a -m "I have added some changes"'
                sh 'git push -u origin new-tf-pr'
            }
        }
    }
}
