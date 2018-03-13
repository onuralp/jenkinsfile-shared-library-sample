@Library('jalogut/jenkins-basic-shared-library-sample') _


parameters {

        string( name: "simpleVar",     defaultValue:"${env.Simple}",	   description: "Evoq Version") 
    string( name: "simpleVar2",     defaultValue:"${env.Simple}",	   description: "Evoq Version") 
        
    }
standardPipeline {
    projectName = "${params.simpleVar}"
    serverDomain = "${params.simpleVar2}"
}
