#!/usr/bin/env groovy
node {
  stage "Validate parameters"
  if(params.Project == '')
    error("Required parameters not specified")
  echo params.Project
  
  sh "mkdir -p output"
  
  writeFile file: "output/usefulfile.txt", text: "This file is useful, need to archive it"

}
