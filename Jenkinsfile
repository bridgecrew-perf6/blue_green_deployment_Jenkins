pipeline 
{
  agent { node { label 'docker_node'}}
    parameters {
        choice(name: 'ENV', choices: ['Deployment','Display','Promote', 'Undo'], description: 'Blue-green deployment Operations')
    }
    stages {
        stage('parameter_choice') {
            steps {
                echo "${params.ENV}"  



            }
        }
    }
}
