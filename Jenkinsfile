pipeline{
    agent{
        label "ansible-agent"
    }
    stages("run ping module"){
        stage{
            steps{
                sh 'ansible -m ping'
            }

        }
    }
}