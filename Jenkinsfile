pipeline{
    agent{
        label 'custom'
    }
    
    stages{
        stage("build"){
            steps{
            sh 'pwd'
            //sh 'cd /home/ubuntu/new && pwd'
            dir("/home/ubuntu/new"){
            git url: 'https://github.com/akshayborse007/test.git'
            
            }    
            }
            
        }
    }
    
}
