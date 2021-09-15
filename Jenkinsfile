node {
    checkout scm
    stage('Build') {
        echo 'iniciando make' 
        sh 'make clean' 
        sh 'make' 
    }
    stage('Test') {
        echo 'Testing...'
    }
    stage('Deploy') {
        echo 'Deploying...'
    }
}