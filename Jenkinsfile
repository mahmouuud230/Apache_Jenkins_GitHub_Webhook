pipeline {
    agent any
    stages {
        stage('Checkout repo') {
            steps {
                git 'https://github.com/mahmouuud230/Apache_Jenkins_GitHub_Webhook.git'
            }
        }

        stage('Print the file content') {
            steps {
                sh 'sudo cp index.html /var/www/html/'
           
            }
        }

        // stage('Cleaning Jenkins Workspace') {
        //     steps {
        //         deleteDir()
           
        //     }
        // }
    

    }
}
