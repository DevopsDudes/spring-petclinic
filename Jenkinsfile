node {
    stage('scm'){
        git 'https://github.com/DevopsDudes/spring-petclinic.git'
    }
    stage('build'){
         sh 'mvn package'
     }
}