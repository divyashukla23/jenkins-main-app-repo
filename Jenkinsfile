@Library('my-shared-lib') _

pipeline {
    agent any

    stages {
        stage('Deploy') {
            steps {
                deployApp(appName: 'MyService', env: 'staging')
            }
        }
    }
}


// pipeline {
//     agent any

//     stages {
//         stage('Greeting') {
//             steps {
//                 helloWorld('Divya')
//             }
//         }
//     }
// }
