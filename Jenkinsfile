    stage ('Dotnet Restore Jenkins Fora') {
        echo 'Hello World! 5 Jenkins Fora'
    }

    stage ('Veracode SCA Scan') {
        echo 'Hello World! 6'
    }

    stage ('SCA SCAN') {
        sh 'curl -sSL  https://download.sourceclear.com/ci.sh | sh -s -- scan --url https://github.com/rafafrika/verademo-dotnet'
    }