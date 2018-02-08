#!/usr/bin/groovy


def numeroSig
def nombre
def librearyName

def runPPCJenkinsfile() {

    def lib = library('projectX-shared-libs').com.evobanco
    def projectUtils = new lib.ProjectUtils()

    node('maven') {

        stage('stage 1') {
            echo "Stage 1"


            numeroSig = lib.ProjectUtils.getNumber(3)
            nombre = lib.ProjectUtils.getName("Carlos")


            libraryName = projectUtils.getLibraryName()

            echo "numero siguiente al 3: ${numeroSig}"
            echo "Nombre (En MAYUSCULAS): ${nombre}"
             echo "Library name: ${libraryName}"
        }

        stage('stage 2') {
            echo "Stage 2"

            hello()
        }
    }
}

return this;