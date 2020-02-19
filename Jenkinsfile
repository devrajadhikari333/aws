node(){
    stage('checkout'){
        checkout scm
    }
    stage('Build'){
        sh "sh variable.sh"
    }
    stage('NOtify'){
        sh " echo THis job run successfully"
    }
}