pipeline{
    agent any
    stages{
        stage("execute playbook"){
            steps{
                ansiblePlaybook credentialsId: '64762a78-c6a5-4dc4-8fb2-8a8f7835fa83', disableHostKeyChecking: true, installation: 'ansible_path', inventory: '/etc/ansible/hosts', playbook: '/etc/ansible/test.yaml'
            }
        }
    }
}
