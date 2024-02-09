pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                script {
                    // Choisissez la commande en fonction de votre script
                     sh 'python hello_world.py' // Pour Python
                    // 'javac HelloWorld.java && java HelloWorld' // Pour Java
                }
            }
        }
    }
}
