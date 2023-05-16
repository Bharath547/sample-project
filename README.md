This is a Hello-World Java application.

There is also a Jenkinsfile that is used for the CI-pipeline using Jenkins.
For that Jenkinsfile, the following paramters are passed:
ApplicationPath - gives the path of the java application. Usually it is the path to the directory where pom.xml file is.
ArtifactsPath - gives the path in which the build artifacts are stored.
SourceURL - gives the url of the source code.
BranchName - gives the branch name to build when the pipeline is triggered.
BrowserClass - gives the type of repository browser.
CheckOutClass - gives the type of Source Code Management.
PrivateKeyID - ID of the Private Key credential in Jenkins.
