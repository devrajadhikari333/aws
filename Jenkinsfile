node(){
    stage('checkout'){
        checkout scm
    }
    stage('Build'){
        sh "sh variable.sh"
    }
    stage('NOtify'){
        sh "THis job run successfully"
    }
}