pipeline {
    agent any
   tools {
     maven 'mvn'
 }
   stages {
        stage('clone the code') {
            steps {
            sh 'git clone https://github.com/anilkumar3577/hello-world-1.git'   
            }
        }
        stage('build my code') {
            steps {
             sh 'mvn package'
            }
        }
    }
}
