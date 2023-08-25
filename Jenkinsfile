pipeline {
    agent any

    stages {
        stage('Checkout stage') {
            steps {
                echo ' Git Clone from SCM'
            }
        }
        stage('CI Stage') {
            steps {
                echo 'Make it as a PKG'
                echo 'send this PKG to artifactory'
            }
        }
        stage('CD Stage') {
            steps {
                echo 'Bring the PKG from artifactory'
                echo 'Deploy this PKG to Target Server'
            }
        }
        
    }
}
