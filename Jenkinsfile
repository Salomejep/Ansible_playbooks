pipeline{
    agent{
        label "ansible-agent"
    }
    stages{
        stage('Run ping command'){
            steps{
                sh 'ansible all -m ping'
            }

        }
    }
}