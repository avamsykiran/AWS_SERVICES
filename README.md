AWS
-------------------------------------------------------------------------------------

    Cloud Services Platform 

    Cloud ??
        Platform or Software or a Infra Strucutre provided as a Service on a remote setup.

    Why Cloud ??
        1. We do not need physical setup on-primises.
            a. eleimate initial setup cost
            b. saves man hours need to maintian the traffic, security and the up time of the servers
        2. We get pay only as per use.
        3. We get to upgrade or change the setup as per the changing needs of the application.
    

    AWS Features

        1. Flexible
        2. Cost Effective
        3. Highly Secure
        4. Scalalbe and Reliable

    Flexible becaue the range of service offered is pretty large. In fact for each
    domain of service we have a minimum of 2 to 5 options of services to choose from.

    Each service comes witha minimumm price wave-off limit and psot which based on the useage
    the bill is provided on prorated. Hence cost effective.

    AWS has spread its data center wide across the global and these data centers are called REGIONS.
    we are expected to choose a region to host our servicem, that is geographically near to the client to
    ensure the uptime and response time.

    AWS Service?

        Domain                                  Service
        ----------------------------------------------------------------
        Networking                              ApiGateway, VPN, VPC, SubNEts, RouteS3
        Security and Identitiy                  IAM, KMS
        Computing                               EC2, Lambda, Elastic BeanStalk, ECS
        Storage                                 S3, Elastic Block Storage,  
        Data Services                           RDS
        Developer Tools                         CodeCommit
        Monitoring Tools                        CloudWatch, QuickSight, 

Start a Spring Boot Rest API with MySQL Persistence On EC2

    Step 1: On your local machine
        We will create a spring boot application that gives one end point to retrive list of Employees
        Test Run the application on the local machine.
        Create a .jar file of the spring boot application.
        Push the .jar fiel into a git repo.

    Step 2:
        Luanch an EC2 Instacne
        Create a RDS DB Instacne and connect it with EC2-Instacne.
        Connect Remote Desktop to EC2 Instacne
        Install JDK and MAven on EC2 Instance
        Pull the .jar file from the git repo
        And invoke the .jhar file using maven.

Assignment

    Deploy a Spring boot rest api with any RDBMS persistence on EC2-RDS setup via AWS Elastic BeanStalk.