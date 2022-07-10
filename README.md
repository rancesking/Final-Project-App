# 🔗 3 Tier Infraestructure with Terraform APP
<p align="center">
<img src="https://www.edupenguin.com/wp-content/uploads/2020/06/hqdefault-30.jpg">
</p>
Terraform is an open-source infrastructure as code software tool that enables you to safely and predictably create, change, and improve infrastructure. Les go and terraform the world. 🦦🦦

## Final project APP

The application to deploy is a simple PERN Stack To do APP, this application with the CI/CD pipeline for create the containers is located in this repository. For this project i was requiered to create and n-tier application on AWS, this insfraescture needs to be on writed on code using IAC principles in this case i use terraform to create my infraescture this infraestructure is located here.[xkingrd/3-tier-infra](https://github.com/rancesking/My-3-tier-app/).

To deploy this project first you need modify the files and push to the repository, the build and deployment of the container images is automated with Github Actions CI/CD pipeline, all the changes made to an application is builded in that container image.

1)[UI Container](https://hub.docker.com/repository/docker/xkingrd/ui-front)

2)[API Container](https://hub.docker.com/repository/docker/xkingrd/api-back)
