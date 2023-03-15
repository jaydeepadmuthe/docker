pipeline {
agent{
label{
		label "built-in"
		customWorkspace "/data3/pipeline/"
}
}

stages {

		stage ("on master"){
			steps {
					sh "docker cp /data3/pipeline/index.html q3:/usr/local/apache2/htdocs/"
			}
		
		}
}
}
