pipeline {
    agent any
    stages{
        stage('Run Playbook'){
            steps{
                sh 'ansible-playbook -i inventory.yaml playbook.yaml -e "ansible_become_password=jenkins"'
            }
        }
    }
}