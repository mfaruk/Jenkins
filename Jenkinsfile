@Library('pipeline-library-demo@master')_
pipeline {
    agent any
    parameters {
        string(name: 'RELEASE_VERSION', defaultValue: '1.0.0', description: 'Application git release tag version')
    }
    environment { 
        ENV_STACK = 'staging'
    }    
    stages {
        parallel{  
        stage('Example') {
            steps {
                echo "Deploying ${params.RELEASE_VERSION} in ${env.ENV_STACK}"
            }
        }        
        stage('Demo') {
            steps{
                echo 'Hello world'
                sayHello 'DaDa'
            }
       }
      }  
        
    }
}

