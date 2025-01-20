pipeline {
    agent any

    environment {
        // Install the Maven version configured as "M3" and add it to the path.
        PATH= "/opt/maven/bin:$PATH"
    }
        
        stage("build"){
            steps{
                sh "mvn clean install"
            }
        }
}
