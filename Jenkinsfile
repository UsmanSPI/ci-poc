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
        junit 'AP'
      }
    }
    stage('STG') {
      steps {
        build 'ap'
      }
    }
  }
}