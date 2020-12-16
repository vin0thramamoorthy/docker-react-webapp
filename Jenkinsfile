//library identifier: 'shared-library@master', 
//retriever: modernSCM([$class: 'GitSCMSource', remote: 'https://github.com/vin0thramamoorthy/shared-library.git'])
//simplePipeline()

@Library('shared-library@master') _

withCredentials([usernamePassword(credentialsId: 'jenkins', passwordVariable: 'react-password', usernameVariable: 'react-username')]) {
    reactbaseBuild {
   	appName = "vinodjuly10/node"
        buildType = "react"
        deployType = "helm-service"
    }
}
