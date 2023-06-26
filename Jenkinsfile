pipeline {
    agent any

    stages
    {
        stage('prpare')
        {
            steps
            {
                echo 'well'
            }
        }
         stage('test')
        {
            steps
            {
                echo 'good'
            }
        }
         stage('deploy')
        {
            steps
            {
                echo 'great'
            }
        }
    }
    post 
    {
        always
        {
            emailext body:'summary', subject:'pipeline status', to:'yadavallisamuelii@gmail.com'
        }    
    }
    
}
