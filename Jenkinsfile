pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                echo 'Hello World'
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
