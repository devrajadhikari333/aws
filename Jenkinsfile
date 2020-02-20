nodes(){
    stage('checkout'){
        checkout scm
    }
    stage('Build'){
        sh "sh variable.sh"
    }
    stage('until'){
        sh "sh until.sh"
    }
    stage('Notify'){
        sh "echo this job will run successfully"
    }
}