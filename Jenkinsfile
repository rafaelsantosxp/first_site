// This shows a simple example of how to archive the build output artifacts.
node ("docker_host") {
    stage("Deploy site"){
    
    def scmVars = checkout scm

    sh "docker-compose up -d"
    }

}
