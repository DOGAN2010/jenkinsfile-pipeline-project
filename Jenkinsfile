 pipeline {
    agent any
    stages {
        stage('run') {
            steps {
                echo 'Dogan_Way to Reinvent Yourself-- new- commit'
                sh 'python --version'
                sh 'python pipeline.py'
            }
        }
    }
}
// pipeline {
//     agent any
//     stages {
//         stage('build') {
//             steps {
//                 echo 'Compiling the java source code'
//                 sh 'javac Hello.java'
//             }
//         }
//         stage('run') {
//             steps {
//                 echo 'Running the compiled java code.'
//                 sh 'java Hello'
//             }
//         }
//     }
// }