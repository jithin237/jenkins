pipeline{
agent { label 'linux' }
stages {
stage('Build')
{
steps {
echo "hello world"
script {
for(int i=0;i<5;++i)
{
echo "printing Number ${i}"
}
}
}
}
stage('Testing')
{
steps {
echo "hello world"
script {
for(int i=0;i<5;++i)
{
echo "printing Test stage ${i}"
}
}
}
}
}
}