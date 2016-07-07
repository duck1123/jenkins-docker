#!groovy

stage 'Build Image'

node {
    checkout scm
    def image = docker.build("duck1123/jenkins")
    image.push()
}
