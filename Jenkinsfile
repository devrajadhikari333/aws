node(){
    stage('checkout'){
        checout scm
    }
    stage('Build'){
        sh "sh variable.sh"
    }
    stage('Array'){
        sh "sh until.sh"
    }
    stage('NOtify'){
        sh "THis job run successfully"
    }
}