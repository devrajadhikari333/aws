node(){
    stage('checkout'){
        checkout scm
    }
    stage('Printing Parameter'){
     sh "echo ${environment}"   
    }
    stage('Build'){
        sh "sh variable.sh"
    }
    stage('array'){
        sh "sh until.sh"
    }
    stage('NOtify'){
        sh " echo THis job run successfully"
    }
}