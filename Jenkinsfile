node
    {
        stage('checkout')
        {
            checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[url: 'https://github.com/NagarjunaTubati/Jenkins-pipeline.git']]])
        }
        
        stage('build')
        {
            echo "build the code"
           
        }
        stage('testing')
        {
            echo "test the code"
        }
        stage('delivery')
        {
            echo "devlivery the code"
        }
    }
