
pipeline {
agent none
stages {
stage('Run Tests') {
parallel {
stage('Test On Windows') {
agent { label "windows" }
steps {
echo "run-tests-windows.bat"
}
}
stage('Test On Linux') {
agent { label "linux" }
steps {
echo "run-tests-linux.sh"
}
}
}
}
}
}
