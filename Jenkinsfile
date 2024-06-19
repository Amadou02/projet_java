node {
   stage('clone') {
        git branch: 'main', credentialsId: '5e549481-c2da-4882-8996-a18641284bee', url: 'https://github.com/Amadou02/projet_java.git'
    }
   stage('build') {
        sh 'javac Main.java'
    }
   stage('run') {
        sh 'java Main'
    }
}
