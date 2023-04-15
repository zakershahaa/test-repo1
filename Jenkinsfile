pipeline 
{
   agent any

    stages
    {
        stage('Build') 
        {
            steps
            {
                echo 'I am building now'
            }
        }
            stage('Test') 
       {
            steps
            {
                echo 'I am testing now'
            }
       }
            stage('Deploy') 
        {
       
            steps
            {
                echo 'I am deploy now'
            }
        }
       stage("Test")
       {
            steps
          {
                // mvn test
                sh "mvn test"
          }
       }
    }
}
