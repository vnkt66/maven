pipeline {
    agent any
    stages {
        stage('Build Stage') {
        steps {
                bat `git add . 
                     git commit -am "jf"`
        }
        }
        stage('Deploy') {
        steps {
                bat `git push -u origin master`
        }
        }
        stage('Release') {
        steps {
               echo "Released Successfully"
        }
        }
    }
}