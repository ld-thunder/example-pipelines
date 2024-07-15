library "cb-days"

podTemplate(
    cloud: cloudPicker(),
    yaml: getPodTemplateYaml("node")
){
    node(POD_LABEL) {
        container("nodejs") {
            sh "node -v"
        }
    }
}
podTemplate(
    cloud: cloudPicker(),
    yaml: getPodTemplateYaml("python")
){
    node(POD_LABEL) {
        container("python") {
            sh "python --version"
        }
    }
}