pipeline {
agent{
label{
		label "built-in"
		customWorkspace "/data1/pipeline/"
}
}

stages {

		stage ("on master"){
			steps {
					sh "docker cp /data1/pipeline/index.html q1:/usr/local/apache2/htdocs/"
			}
		
		}
}
}
