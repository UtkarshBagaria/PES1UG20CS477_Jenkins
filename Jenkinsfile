pipeline
{
    agent any
    stages
    {
        stage('Build')
        {
            steps
            {
                sh 'g++ pes1ug20cs477.cpp'
                sh '/var/jenkins_home/workspace/pes1ug20cs477-1/main/hello_exec'
                echo 'Build Stage Successful'
            }
        }
        stage('Test')
        {
            steps
            {   
                sh './a.out'
                echo 'Output from cpp file'
            }
        }
        stage('Deploy')
        {
            steps
            {
                echo 'Deploying...'
            }
        }
    }
}