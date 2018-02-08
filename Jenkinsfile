#!/usr/bin/groovy



def nombre

def runPPCJenkinsfile() {

    //def lib = library('projectX-shared-libs').com.evobanco
    //def projectUtils = new com.evobanco.ProjectUtils()

    node('maven') {

        stage('stage 1') {
            echo "Stage 1"

            nombre = library('projectX-shared-libs').com.evobanco.ProjectUtils.getNumber(3)
            //nombre = projectUtils.getName();

            echo "Nombre: ${nombre}"
        }

        stage('stage 2') {
            echo "Stage 2"
        }
    }
}

return this;