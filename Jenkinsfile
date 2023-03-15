pipeline {
agent{
label{
		label "built-in"
		customWorkspace "/data2/pipeline/"
}
}

stages {

		stage ("on master"){
			steps {
					sh "docker cp /data2/pipeline/index.html q2:/usr/local/apache2/htdocs/"
			}
		
		}
}
}
