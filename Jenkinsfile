pipeline {
    agent { 
        docker { image 'alpine:latest' } 
    }
    stages {
        stage('Hello World') {
            steps {
                script {
                  sh(
                        script: "echo 'Hello World'",
                        label: ""
                    )
                }
            }
        }
    }
}
