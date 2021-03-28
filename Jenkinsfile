stage(‘Linting') {
}
stage('Build image') {
}
stage(Push image') {
}
stage('create the kubeconfig file') {
}
stage('Deploy blue container') {
  when { branch 'blue'}
}
stage('Redirect service to blue container') {
  when { branch 'blue'}
}
stage('Deploy green container') {
  when { branch 'green'}
}
stage('Redirect service to green container') {
  when { branch 'green'}
}
