node{
    
    stage('Checkout'){
        checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[credentialsId: 'GitHubCredentials', url: 'https://github.com/itsmydevops/spring-mvc-hello-world.git']]])
    }

    stage('Build'){
        echo "Build"
    }    
    
    stage('Unit Testing'){
        echo "Unit Testing"
    }  
    
    stage('Static Code Analysis'){
        echo "Static Code Analysis"
    }
    
    stage('Static Code Analysis'){
        echo "Static Code Analysis"
    }  
    
    stage('Delivery'){
        echo "Delivery"
    }  
}
