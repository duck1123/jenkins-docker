#!groovy

stage 'Build Image'

node {
    def image = docker.build("duck1123/jenkins")
    image.push()
}
