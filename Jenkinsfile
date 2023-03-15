pipeline {
agent{
label{
		label "built-in"
		customWorkspace "/data/pipeline"
}
}

stages {

		stage ("on master"){
			steps {
					sh "docker cp /data/pipeline q1:/usr/local/htdocs/"
			}
		
		}
}
}
