pipeline {
    agent {
        node{
            label 'maven'
        }
    }

    stages {
        stage('clone-code') {
            steps {
                git branch: 'main', url: 'https://github.com/Prajwal-2022/tweet-trend-new.git'
            }
        }
    }
}
