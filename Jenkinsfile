pipeline{
    agent{
        label "ansible-agent"
    }
    stages{
        stage('run ping command'){
            steps{
                sh 'ansible all -m ping'
            }

        }
    }
}