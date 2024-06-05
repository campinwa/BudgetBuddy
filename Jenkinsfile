pipeline {
    agent any 

    stages {
        stage('Initialize') {
            steps {
                script {
                    echo "🎉 The job was automatically triggered by a push event."
                }
            }
        }
        
        stage('Run on OS') {
            steps {
                script {
                    echo "🐧 This job is now running on a ${env.NODE_NAME} server hosted by Jenkins!"
                }
            }
        }

        stage('Branch and Repo Info') {
            steps {
                script {
                    echo "🔎 The name of your branch is ${env.BRANCH_NAME} and your repository is ${env.GIT_URL}."
                }
            }
        }

        stage('Checkout Code') {
            steps {
                checkout scm
                script {
                    echo "💡 The repository has been cloned to the runner."
                }
            }
        }

        stage('Test Code') {
            steps {
                script {
                    echo "🖥️ The workflow is now ready to test your code on the runner."
                }
            }
        }

        stage('List Files') {
            steps {
                script {
                    sh 'ls ${WORKSPACE}'
                }
            }
        }

        stage('Job Status') {
            steps {
                script {
                    echo "🍏 This job's status is ${currentBuild.currentResult}."
                }
            }
        }
    }
}
