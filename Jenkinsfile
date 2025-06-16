pipeline {   
    agent any

    stages {   
        stage('Master branch') { 
            steps { 
               sh 'echo "This is master branch"' 
            }
        }
     
        stage('sprint1') { 
            steps { 
               sh 'echo "this is sprint1 branch!!!!!"'
            }
        }

        stage("Deploy application") { 
             steps { 
                sh 'echo "this is Deploying branch..."'
            }
        }  
    }
}
