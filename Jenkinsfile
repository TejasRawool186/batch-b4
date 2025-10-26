pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
               git branch: 'main', credentialsId: 'cc789cd2-04e9-483c-8463-de01675cbfee', url: 'https://github.com/TejasRawool186/batch-b4.git'
            }
        }
      stage('Compile') {
            steps {
                bat "javac HelloWorld.java"
            }
        }
      stage('Run') {
            steps {
                bat "java HelloWorld"
            }
        }
    }
}
