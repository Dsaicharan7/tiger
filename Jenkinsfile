pipeline
{
agent any
stages
{
stage ('cloning code from github')
{
steps
{
git url: 'https://github.com/RavitejaAdepudi/javawar.git'
}
}
stage ('building the code')
{
steps
{
sh 'touch manipulate.txt'
}
}
stage ('testing the code')
{
steps
{
sh 'touch def.txt'
}
}
stage ('deploying the code')
{
steps
{
sh 'touch xyz.txt'
}
}
}
}
