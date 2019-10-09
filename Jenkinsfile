node
{
    stage("checkout")
    {
        checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[url: 'https://github.com/yak16/Test3.git']]])
    }

    stage("Compile & Build")
    {
        echo "Compile and Build"
    }
    
    stage("Test & Deploy")
    {
        echo "Test & Deploy"
    }
    
    stage("Deployment")
    {
        echo "Deployment"
    }
}
