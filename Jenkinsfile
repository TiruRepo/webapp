pipeline {  
    agent any
    tools{
        maven "maven-3.9.9"
    }
    stages {
        stage('Git Clone') {
            steps {
               git 'https://github.com/ashokitschool/maven-web-app.git'
            }
        }
        stage('Build') {
            steps {
               sh 'mvn clean package'
            }
        }        
      
    }
}
