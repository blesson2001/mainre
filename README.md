# mainre

Hi,

In order to create a 3 environment we can set that as 3 branches in github. which are production,staging and dev

To set the CI/CD pipe line

We need to install ajenkins server and install plugin for github.

Then we need to copy the files from  git branch to the mounted valume which is in the jenkins and the production infra.

we need to create the listed files in infra

deployment.yaml
ingress.yaml
service.yaml
secret.yaml

for autoscalling we need to do the hpa.yaml file.
