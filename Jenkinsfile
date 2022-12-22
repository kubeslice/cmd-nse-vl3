@Library('jenkins-library@opensource') _
dockerImagePipeline(
  script: this,
  service: 'cmd-nse-vl3',
  dockerfile: 'Dockerfile',
  buildContext: '.',
  buildArguments: [PLATFORM:"amd64"]
  
)
