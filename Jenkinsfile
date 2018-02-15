pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh '''#bin/sh

# need wirite a build script'''
      }
    }
    stage('Test') {
      steps {
        build 'aws'
      }
    }
    stage('STG') {
      steps {
        awaitDeploymentCompletion 'xzd cd cdd'
      }
    }
  }
}