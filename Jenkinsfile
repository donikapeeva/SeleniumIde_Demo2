pipeline {
    agent any

    stages{
        stage("Checkout code") {
          //checkout the repository
          steps {
            git branch: 'main', url: 'https://github.com/donikapeeva/SeleniumIde_Demo2'
          }
        }
        stage("Set up .Net Core") {
          //install dotnet
        }
        stage("Restore dependencies") {
          //install dependencies
        }
        stage("Build") {
          //build
        }
        stage("Run tests") {
         //run tests
        }
    }
}