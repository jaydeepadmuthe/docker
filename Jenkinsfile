pipeline {
agent{
label{
		label "built-in"
		customWorkspace "/data3/pipeline/index.html"
}
}

stages {

		stage ("on master"){
			steps {
					sh "docker cp /data/pipeline/index.html q1:/usr/local/apache2/htdocs/"
			}
		
		}
}
}
