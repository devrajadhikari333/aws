node(){
    stage('checkout'){
        checkout scm
    }
    stage('Build'){
        sh "sh variable.sh" // hope it runs
    }
    stage('until'){
        sh "sh until.sh"
    }
    stage('Notify'){
        sh "echo this job will run successfully"
    }
}