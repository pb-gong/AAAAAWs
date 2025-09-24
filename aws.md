The key advantage of using AWS Global Infrastructure is
-   No need to worry about heavy initial investment costs(upfront costs)
-   AWS takes care about the required the minimum capacity/scale for your service on your half
-   So, you can easily make a decision to up/down your sevices's capacity/scale with only a few minutes' notice

AWS provides the Core Serviecs such as

-   Computing
        - EC2
          A virtual machine launched on AWS hardware
          You can launch your Websites/Databases what you would do on a typical server
          You can easily sale up/down your machine by changing the EC2 instance type and size
          EC2 provies a broad variety of instance types so you can pick one specific to what your workload needs
        
        - Serverless Resources (like Lambda)
          You do not need to provision or manage servers yourself
          Resources automatically scale up or down based on usage
          Built-in availability and fault tolerance are provided by default
          Pricing is pay-as-you-go, you only pay for actual usage(per millisecond)
          Reduces operational overhead (no installation, maintenance, or patching of servers)
          Allows you to focus on business logic instead of infrastructure management
          Optimizes cost by not charging for idle resources

        - Containers
          - ECS (Elastic Container Service)
          A fully managed container orchestration service provided by AWS
          Runs Docker containers on AWS, either on EC2 instances or with Fargate (serverless option)
          Deep integration with AWS services (IAM, CloudWatch, ALB, etc.)
          Easier to set up and manage compared to Kubernetes
          Great for AWS-centric workloads where simplicity is important

          - EKS (Elastic Kubernetes Service)
          A fully managed Kubernetes control plane service on AWS
          Provides standard Kubernetes API, allowing portability across cloud and on-premises environments
          Lets you run and scale Kubernetes workloads without managing the control plane
          Compatible with Kubernetes ecosystem tools (Helm charts, plugins, etc.)
          Best suited for large-scale or complex applications that benefit from Kubernetes flexibility

          - Key Benefits of Using Containers
          Automates container orchestration (deployment, scaling, recovery)
          Improves resource efficiency, reducing costs
          Enables microservices architectures and CI/CD pipelines
          Provides high availability and security through AWS integration