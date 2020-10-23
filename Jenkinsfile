node
{
    stage('Checkout')
    {
        checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[url: 'https://github.com/Swathi199654/gittest.git']]])
        workspace =pwd()
        
    }
    stage('Static Code ansalysis')
    {
        echo "Static Code ansalysis"
    }
    stage('Build')
    {
        echo "Build"
    }
    stage('Unit Testing')
    {
        echo "Unit Testing"
    }
    stage('Delivey')
    {
        echo "Deliver the code"
    }
}
