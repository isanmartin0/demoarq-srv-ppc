#!/usr/bin/groovy
@Library('projectX-shared-libs')_


def nombre

def runPPCJenkinsfile() {

    def projectUtils = new com.evobanco.ProjectUtils()

    node('maven') {

        stage('stage 1') {
            echo "Stage 1"
            nombre = projectUtils.getName();
            echo "Nombre: ${nombre}"
        }

        stage('stage 2') {
            echo "Stage 2"
        }
    }
}

return this;