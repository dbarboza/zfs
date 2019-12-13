pipeline {
  agent {
    docker {
      image 'ubuntu/xenial'
    }

  }
  stages {
    stage('build') {
      steps {
        sh 'apt update; apt-get install build-essential autoconf automake libtool gawk alien fakeroot gdebi-core zlib1g-dev uuid-dev libattr1-dev libblkid-dev libselinux-dev libudev-dev libacl1-dev libaio-dev libdevmapper-dev libssl-dev libelf-dev linux-headers-$(uname -r) python3 python3-dev python3-setuptools python3-cffi'
      }
    }

  }
}