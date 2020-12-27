# jenkins_pipeline_homework

In this repo you can find two files:

- package_pipeline_jenkinsfile: this files contains a pipeline job in jenkins with one step : Get some code from a GitHub repository and run "mvn clean package" to compile the code.

on success, the jobs saves the war files using the archiveArtifacts command and builds the other jobs called deliver_package_pipeline.
