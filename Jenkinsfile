pipeline {
    agent any
    stages {
        stage ('scm') {
            steps {
                git 'https://github.com/DevopsDudes/spring-petclinic.git'
            }
        }
        stage ('Package') {
            steps {
                sh 'mvn package'
            }
        }
    }
}