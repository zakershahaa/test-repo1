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
           post
           {
              sh '''
              ls
              pwd
              date
              calander
              '''
        }
    }
}
