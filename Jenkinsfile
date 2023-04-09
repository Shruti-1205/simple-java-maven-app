pipeline {
    agent any

    tools {
        maven 'Maven 3.8.3'
        jdk '11'
    }

    stages {
        stage('Build') { 
            steps {
                sh 'mvn -B -DskipTests clean package' 
            }
        }
    }
}
