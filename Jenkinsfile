node {
        stage('Clone') { 
            git 'https://github.com/Toufa1/my-jenkins-file.git'
        }
        stage('Build') { 
            sh label: '', script: 'javac Main.java'
        }
        stage('Run') { 
            sh label: '', script: 'java Main'
        }
}

