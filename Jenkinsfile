// node {
//     stage('scm'){
//         git 'https://github.com/DevopsDudes/spring-petclinic.git'
//     }
//     stage('build'){
//         sh 'mvn clean package'
//     }
// }
pipeline {
    agent any
    stages{
        stage{'scm'}{
            step{
                git 'https://github.com/DevopsDudes/spring-petclinic.git'
            }
        }stage{'Package'}{
            step{
                sh 'mvn package'
            }
        }
    }
}