node {
    // Get Artifactory server instance, defined in the Artifactory Plugin administration page.
    //def server = Artifactory.server "SERVER_ID"
    // Create an Artifactory Maven instance.
    //def rtMaven = Artifactory.newMavenBuild()
    def buildInfo

    stage('Clone sources') {
        git url: 'https://github.com/sidde3/spring-jpa.git'
    }

    stage('Maven build') {
        //buildInfo = rtMaven.run pom: 'maven-example/pom.xml', goals: 'clean package'
        sh 'mvn clean package'
    }
}