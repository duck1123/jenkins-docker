#!groovy

stage 'Build Image'

node {
    checkout scm
    def image = docker.build("repo.jiksnu.org/duck1123/jenkins")
    image.push()
}
