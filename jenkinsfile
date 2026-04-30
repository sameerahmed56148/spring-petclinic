pipeline {
    agent any

    stages {
        stage('git clone') {
            steps {
              git branch: 'main', url: 'https://github.com/sameerahmed56148/spring-petclinic.git'  
            }
        }
        stage('build') {
            steps {
             sh 'mvn package'   
            }
        }
    }
