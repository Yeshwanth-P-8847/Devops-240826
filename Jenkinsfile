pipeline{
    agent any

    stages{
        stage('Hostname'){
            steps{
                sh 'hostname'
            }

        }

        stage('Memory Usage'){
            steps{
                sh 'free -h'
            }

        }

        stage('Disk Usage'){
            steps{
                sh 'df -kh'
            }
        }

        stage('CPU Details'){
            steps{
                sh 'lscpu'
            }
        }
    }
}
