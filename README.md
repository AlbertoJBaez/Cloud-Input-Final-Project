# Bootcamp's Final Project: the Cloud & DevOps team input

This repository corresponds to the Cloud and DevOps team's contribution to the [The Bridge](https://www.thebridge.tech/?utm_medium=ppc&utm_source=adwords&utm_campaign=GA_The+Bridge_Marca&utm_term=the%20bridge%20bootcamp&hsa_kw=the%20bridge%20bootcamp&hsa_net=adwords&hsa_ver=3&hsa_cam=6496961935&hsa_ad=549241137266&hsa_acc=1272778203&hsa_src=g&hsa_grp=82036397030&hsa_mt=p&hsa_tgt=kwd-1287381892718&gclid=Cj0KCQjw06-oBhC6ARIsAGuzdw3wywTfvzIW39JlTTrYJZYpkwF0yUkijjEy_5Isn9yp4Dv70WAwjewaAu5zEALw_wcB) Bootcamp end-of-course project.

## The project 

[The project](https://github.com/desafioteam1) was focused on solving a problem raised in a brief and value the experience of each team (UX UI product design, cybersecurity, data science, full stack web development, digital marketing and cloud/devOps).

Goals of the project:

- Complex problem solving.
- Work with agile methodologies, in a realistic work situation with multidisciplinary teams.
- Development of a project under the pressure of deadlines and the presentation of the project before a jury.

The team of Cloud and DevOps would have a series of duties to deliver a complete Cloud solution to the project.

## The contribution of Cloud and Devops team

### Technical requirements of the Cloud & DevOps input to the project

- *Select the Cloud account associated with the project group*. Find a way to get free for the duration of the crew challenge.

- *Establish the team members who will have access to the project*. Create access levels and resource allocation.

- *Cloud infrastructure deployment: Design a cloud infrastructure using AWS, Azure or GCP services.* The architecture to be set up must be properly painted in the corresponding tools.

- *Infrastructure automation and management: The provisioning and management of cloud infrastructure should be automated.* This involves defining and deploying infrastructure as code (Infrastructure as Code) and using automation techniques to configure and update it.

- *Implementation of CI/CD pipelines:* Students must establish a continuous integration and continuous delivery (CI/CD) flow. They must build an application that allows the automated construction and deployment of the developed application or services.

- *Define the CI architecture according to the type and language of the application to be developed.*

- *Define the CD architecture according to the objective (Dev only, Dev and Prod).* Monitoring and log management: Implement a monitoring solution where developers can check the status of their deployed solution at all times.

- *Security and compliance:* Students must secure the infrastructure and application through good security practices so that it cannot be misused by elements outside the organisation or misused by elements within the organisation.

###  Cloud service selection

Amazon Web Services (AWS) stands out as an ideal choice for running a cloud project in a bootcamp course for several key reasons. First, AWS's wide range of services provides a scalable and flexible infrastructure that adapts to the specific needs of any project. From compute and storage to artificial intelligence and machine learning, AWS offers a wide variety of services that allow students to explore and apply a wide range of technologies in their project.

In addition, AWS's ease of use and comprehensive documentation make it accessible to beginners and students alike. The intuitive web administration console allows services to be configured and managed without a steep learning curve, which is especially beneficial in an educational environment where time is limited. In addition, AWS provides educational resources such as tutorials, hands-on labs and certifications that complement classroom learning and allow students to acquire practical, industry-recognised skills.

Another key advantage is the global presence of AWS and its data centres. This means that students can deploy their project in a wide variety of locations, which is valuable both for the global availability of the project and for the hands-on experience of working with a worldwide cloud infrastructure. In short, the versatility, accessibility and educational resources provided by AWS make it an ideal choice for bootcamp students wishing to undertake end-of-course cloud projects.

### Assign permissions by teams and project members.

Of the various project teams, we will assign permissions to those who will be stakeholders of the cloud architecture. These are: 

- Full stack,
- Data, full stack, and
- Cybersecurity.

In a cloud development environment, AWS's IAM (Identity and Access Management) permissions management is essential to ensure the security and efficiency of resources. The Full Stack, Data and Cybersecurity teams have different roles and specific needs.

For the Full Stack team, it is essential to provide access to cloud computing services and databases, but restrict access to critical configurations to prevent unintentional errors.

The Data team needs permissions to access data storage, processing and analysis services, but infrastructure changes must be limited to maintain stability.

As for the Cybersecurity team, they should be granted access to monitor and audit services for potential threats, but not allow changes without approval.

Establishing these permission levels ensures that each team can do its job effectively and securely, while protecting critical cloud resources.


### Cloud infrastructure deployment

To meet the technical requirements of the project, we will aim to build a reliable, resilient and safe architecture. 

The approach we will follow for deployment will be the one outlined in the official guide on how to [Deploy applications on AWS App Runner with GitHub Actions](https://aws.amazon.com/es/blogs/containers/deploy-applications-in-aws-app-runner-with-github-actions/).

AWS App Runner is a fully orchestrated platform that simplifies the deployment of web applications in containers and APIs.  We will start from a container image with ECR and App Runner will orchestrate the creation, scaling and fortification of the application in the AWS cloud environment. For data provisioning, we will create a pipeline on GitHub actions that will ensure continuous, secure and efficient provisioning and deployment of data for our deployment. 

#### The components of our deployment 

We will have to make sure to build a pipeline that ensures the smooth and stable provisioning of data following **CI/CD** best practices. 

- Services: GitHub Actions.
  
Once the provisioning is adequate, we will launch the data provided by the Full-Stack and Data team to **deploy the application in the cloud**.

- Services: AWS App runner, AWS ECR, AWS RDS, Docker.

The deployment must **comply with the required security standards**. This will be done under the guidelines of the cyber security team, who will have the necessary permissions to request the relevant security services in our cloud.

- Services: AWS Firewall Manager, AWS Firewall Manager

With all these components we would have a completely functional cloud infrastructure. 

#### Cloud architecture representation

![Arquitectura Cloud](https://github.com/AlbertoJBaez/Cloud-Input-Final-Project/blob/main/Assets/Arquitectura-Cloud-Proyecto-nitido.png)

<!--

### Infrastructure automation and management: The provisioning and management of cloud infrastructure should be automated.* This involves defining and deploying infrastructure as code (Infrastructure as Code) and using automation techniques to configure and update it.



IMAGENES


![GithubActions](https://github.com/AlbertoJBaez/Cloud-Input-Final-Project/blob/main/Assets/GitHub%20Actions.png)
![Apprunner](https://github.com/AlbertoJBaez/Cloud-Input-Final-Project/blob/main/Assets/aws-app-runner.jfif) 
![AWS ECR] 
![RDS] 
![Docker]
### Implementation of CI/CD pipelines:* Students must establish a continuous integration and continuous delivery (CI/CD) flow. They must build an application that allows the automated construction and deployment of the developed application or services.

- *Define the CI architecture according to the type and language of the application to be developed.*

- *Define the CD architecture according to the objective (Dev only, Dev and Prod).* Monitoring and log management: Implement a monitoring solution where developers can check the status of their deployed solution at all times.

### Security and compliance:* Students must secure the infrastructure and application through good security practices so that it cannot be misused by elements outside the organisation or misused by elements within the organisation.

-->


