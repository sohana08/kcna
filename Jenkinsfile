pipeline {
    agent any    
    stages {
        stage('kcna') {
            steps {
                echo "You are doing good, poll scm"
            }
        }
        
        stage('change') {
            steps {
                sh '''
                    ls
                    cat file2
                '''
            }
        }
    }
}
