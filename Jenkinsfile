pipeline {
agent{
label{
		label "built-in"
		customWorkspace "/data1/pipeline/index.html"
}
}

stages {

		stage ("on master"){
			steps {
					sh "docker cp /data/pipeline q1:/usr/local/apache2/htdocs/"
			}
		
		}
}
}
