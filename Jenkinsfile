pipeline{
    agent any
    stages{
        stage('git clone'){
            steps{
                git branch: 'main', credentialsId: 'github_rahul_password', url: 'https://github.com/rahulm2782/jenkins_testing.git'
            }
        }
        stage('check python version'){
            steps{
                sh 'which uv'
            }
        }
        stage('where am i?'){
            steps{
                sh "pwd"
            }
        }
    }
}