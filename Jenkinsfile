#!/usr/bin/groovy


def numeroSig
def nombre

def runPPCJenkinsfile() {

    //def lib = library('projectX-shared-libs').com.evobanco
    def libUtils = library('projectX-shared-libs').com.evobanco.ProjectUtils()
    //def projectUtils = new com.evobanco.ProjectUtils()

    node('maven') {

        stage('stage 1') {
            echo "Stage 1"


            //numeroSig = lib.ProjectUtils.getNumber(3)
            //nombre = lib.ProjectUtils.getName("Carlos")

            numeroSig = libUtils.getNumber(3)
            nombre = libUtils.getName("Carlos")

            libUtils

            echo "numero siguiente al 3: ${numeroSig}"
            echo "Nombre (En MAYUSCULAS): ${nombre}"
        }

        stage('stage 2') {
            echo "Stage 2"

            hello()
        }
    }
}

return this;