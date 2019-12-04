pipeline {
    agent any

    stages {
        stage("package") {
            steps {
                checkout scm
                bat 'mvn package'
            }
        }
    }
}
