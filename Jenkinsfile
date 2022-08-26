pipeline {
    agent any
    stages{
        stage('Run Playbook'){
            steps{
                sh 'ansible-playbook -i invetory.yaml playook.yaml'
            }
        }
    }
}