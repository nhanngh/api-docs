# Description
Use Maven to deploy api-contracts to Sonatype Nexus Repository.

# How to run
### Install to local repository or remote repository 
- Package and install the repository locally <br>
`mvn clean install`

- Or, if you want to deploy it to a remote repository (You need to set up Sonatype Nexus Repository with the repository name **api-docs-storage**) <br> 
`mvn clean deploy` <br> or <br> `mvn --settings ~/settings.xml clean compile` With the **settings.xml** containing credentials information to access the remote repository.

### [Project example](https://github.com/nhanngh/demo-load-api-docs/) use api-contracts
