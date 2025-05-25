pipeline {   
    agent any

    stages {   
        stage('Master') { 
            steps { 
               sh 'echo "This is the hotfix branch"' 
            }
        }
     
        stage('sprint1') { 
            steps { 
               sh 'echo "This is Sprint1 branch"'
            }
        }

        stage("hotfix") { 
             steps { 
                sh 'echo "This is hotfix branch"'
            }
        }  
    }
}
