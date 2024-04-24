// multistage
pipeline {
    agent any

        stages {
            stage('Source') {
                steps {
                    git url: 'https://github.com/Prakruthi0306/nodejs-docs-hello-world.git'
                }
            }
            stage('Build') {
                steps {
                    script {
                        def mvnHome = tool 'Maven'
                        bat "${mvnHome}\\bin\\mvn -B verify"
                    }
                }
            }
      
            
                                    
        }
}
