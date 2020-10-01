#!/usr/bin/env groovy
node {
  stage "Validate parameters"
  if(params.Project == '' || params.Environment == '')
    error("Required parameters not specified")
  echo "Project update: " + params.Project + " Environment: " + params.Environment
  
  sh "mkdir -p output"
  
  writeFile file: "output/usefulfile.txt", text: "This file is useful, need to archive it"

}
