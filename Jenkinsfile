pipeline {
    agent any
    stages {
        stage('Example') {
            when { 
                anyOf { 
                    branch 'master'; 
                    branch 'dev'; 
                    branch 'test' 
                } 
            }
            steps {
                echo 'Running on master, dev, or test branch.'
            }
        }
    }
}
