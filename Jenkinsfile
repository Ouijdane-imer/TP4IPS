pipeline{
    agent any
    environment {
        VAR = "${params.VAR}"
    }
    stages {
        stage("Display param") {
            steps {
                script {
                    if(VAR)
                    {
                      Echo “my value is true”
                    }
                    else if(VAR)
                    {
                         Echo “my value is false”

                    }
                  
                }
            }
        }
    }
}
