node {
    def tag = "heha"
        env.BUILD_TAG = tag
    
    parameters {
        string(name: 'TAG', defaultValue: 'Mr Jenkins', description: '')
    }
    
    stage('Checkstyle -> Tests -> Deploy to Nexus (where applicable)') {
       sh 'printenv'
    }
   
}
