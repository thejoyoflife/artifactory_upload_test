node {
 def server = Artifactory.server 'my_artifactory_server'

  def uploadSpec = """{
    "files": [{
                "pattern": "hello.txt",
                "target": "my_artifacts"
            }
        ]
    }"""

  server.upload(uploadSpec)
}