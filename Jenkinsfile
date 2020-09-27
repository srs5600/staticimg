pipeline {				//indicate the job is written in Declarative Pipeline
    agent any				//agent specifies where the pipeline will execute. 
    stages {
        stage ("build") {		//an arbitrary stage name
            steps {
                build 'mergeandbuild'	//this is where we specify which job to invoke.
            }
        }
    }
}
