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
               echo "I am ishaque"
            }
       }
            stage('Deploy') 
        {
       
            steps
            {
                echo 'I am deploy now'
            }
        }
       stage("Test mvn")
       {
            steps
          {
                // mvn test
                sh "mvn test"
          }
       }
    }
}
