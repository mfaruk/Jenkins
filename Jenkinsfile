//parallel example
pipeline {
agent none
stages {
stage('Run Tests') {
parallel {
stage('Test On Windows') {
steps {
echo "run-tests-windows.bat"
}
}
stage('Test On Linux') {
steps {
echo "run-tests-linux.sh"
}
}
}
}
}
}
