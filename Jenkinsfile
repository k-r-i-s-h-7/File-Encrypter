node('docker-agent') {

    stage('Checkout') {
        checkout scm
    }

    stage('Build') {
        sh '''
            echo "Running on node:"
            hostname
            pwd
        '''
    }
}