pipeline {
    agent any
    stages {
        stage ('Build BackEnd') {
            steps {
                sh 'mvn clean package -DskipTest=true'
            }
        }
    }
}
