//node {
//    def app

//     stage('Clone repository') {
      

//         checkout scm
//     }

//     stage('Build image') {
//         // build an image locally atinav/test:latest
//        app = docker.build("atinav/test")
//        app.inside {
//         sh 'echo "Tests passed 1"'
//        }
    }
    
    
    node {
    checkout scm

    def customImage = docker.build("my-image:${env.BUILD_ID}")

//     customImage.inside {
//         sh 'make test'
//     }
}

    
    

    // stage('Test image') {
  

    //     app.inside {
    //         sh 'echo "Tests passed"'
    //     }
    // }

    // stage('Push image') {
        
    //     docker.withRegistry('https://registry.hub.docker.com', 'dockerhub') {
    //         app.push("${env.BUILD_NUMBER}")
    //     }
    // }
    
    // stage('Trigger ManifestUpdate') {
    //             echo "triggering updatemanifestjob"
    //             build job: 'updatemanifest', parameters: [string(name: 'DOCKERTAG', value: env.BUILD_NUMBER)]
    //     }
}
