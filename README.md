# Project-VM-docker
This is a combined class project with docker and docker-compose.

1. The Vagrant file is ubuntu based with required installation steps for docker package upon boot up.
2. The following subdirectories contain specific REAME file from class notes.
.
├── EntryCMD
│   └── Dockerfile
├── composetest
│   ├── Dockerfile
│   ├.
├── EntryCMD
│   └── Dockerfile
├── composetest
│   ├── Dockerfile
│   ├── app.py
│   ├── compose.yaml
│   ├── compose.yamlV1
│   └── requirements.txt
├── nano
│   ├── Dockerfile
│   └── nano.tar.gz
└── vprofile-project
    ├── Docker-files
    │   ├── app
    │   │   ├── Dockerfile
── app.py
│   ├── compose.yaml
│   ├── compose.yamlV1
│   └── requirements.txt
├── nano
│   ├── Dockerfile
│   └── nano.tar.gz
└── vprofile-project
    ├── Docker-files
    │   ├── app
    │   │   ├── Dockerfile
    │   │   └── multistage
    │   │       └── Dockerfile
    │   ├── d.txt
    │   ├── db
    │   │   ├── Dockerfile
    │   │   └── db_backup.sql
    │   └── web
    │       ├── Dockerfile
    │       └── nginvproapp.conf
    ├── README.md
    ├── ansible
    │   └── vprofile.yml
    ├── compose
    │   └── docker-compose.yml
    ├── kubefiles
    │   └── vproappdep.yml
    ├── pom.xml
    ├── src
    │   ├── main
    │   │   ├── java
    │   │   │   └── com
    │   │   │       └── visualpathit
    │   │   │           └── account
    │   │   │               ├── beans
    │   │   │               │   └── Components.java
    │   │   │               ├── controller
    │   │   │               │   ├── ElasticSearchController.java
    │   │   │               │   ├── FileUploadController.java
    │   │   │               │   └── UserController.java
    │   │   │               ├── model
    │   │   │               │   ├── Role.java
    │   │   │               │   └── User.java
    │   │   │               ├── repository
    │   │   │               │   ├── RoleRepository.java
    │   │   │               │   └── UserRepository.java
    │   │   │               ├── service
    │   │   │               │   ├── ConsumerService.java
    │   │   │               │   ├── ConsumerServiceImpl.java
    │   │   │               │   ├── ProducerService.java
    │   │   │               │   ├── ProducerServiceImpl.java
    │   │   │               │   ├── SecurityService.java
    │   │   │               │   ├── SecurityServiceImpl.java
    │   │   │               │   ├── UserDetailsServiceImpl.java
    │   │   │               │   ├── UserService.java
    │   │   │               │   └── UserServiceImpl.java
    │   │   │               ├── utils
    │   │   │               │   ├── ElasticsearchUtil.java
    │   │   │               │   ├── MemcachedUtils.java
    │   │   │               │   └── RabbitMqUtil.java
    │   │   │               └── validator
    │   │   │                   └── UserValidator.java
    │   │   ├── resources
    │   │   │   ├── application.properties
    │   │   │   ├── db_backup.sql
    │   │   │   ├── logback.xml
    │   │   │   └── validation.properties
    │   │   └── webapp
    │   │       ├── WEB-INF
    │   │       │   ├── appconfig-data.xml
    │   │       │   ├── appconfig-mvc.xml
    │   │       │   ├── appconfig-rabbitmq.xml
    │   │       │   ├── appconfig-root.xml
    │   │       │   ├── appconfig-security.xml
    │   │       │   ├── views
    │   │       │   │   ├── elasticeSearchRes.jsp
    │   │       │   │   ├── index_home.jsp
    │   │       │   │   ├── login.jsp
    │   │       │   │   ├── rabbitmq.jsp
    │   │       │   │   ├── registration.jsp
    │   │       │   │   ├── upload.jsp
    │   │       │   │   ├── user.jsp
    │   │       │   │   ├── userList.jsp
    │   │       │   │   ├── userUpdate.jsp
    │   │       │   │   └── welcome.jsp
    │   │       │   └── web.xml
    │   │       └── resources
    │   │           ├── Images
    │   │           │   ├── background.png
    │   │           │   ├── header.jpg
    │   │           │   ├── technologies
    │   │           │   │   ├── Ansible_logo.png
    │   │           │   │   ├── Vagrant.png
    │   │           │   │   ├── aws.png
    │   │           │   │   ├── docker.png
    │   │           │   │   ├── git.jpg
    │   │           │   │   ├── jenkins.png
    │   │           │   │   ├── puppet.jpg
    │   │           │   │   └── python-logo.png
    │   │           │   ├── user
    │   │           │   │   ├── giphy.gif
    │   │           │   │   ├── logo.png
    │   │           │   │   ├── user.png
    │   │           │   │   ├── user2.png
    │   │           │   │   └── user3.png
    │   │           │   ├── visualpath.png
    │   │           │   ├── visualpathlogo2.png
    │   │           │   └── visualpathlogo3.png
    │   │           ├── css
    │   │           │   ├── bootstrap.min.css
    │   │           │   ├── common.css
    │   │           │   ├── profile.css
    │   │           │   └── w3.css
    │   │           └── js
    │   │               └── bootstrap.min.js
    │   └── test
    │       └── java
    │           └── com
    │               └── visualpathit
    │                   └── account
    │                       ├── controllerTest
    │                       │   ├── SampleTest.java
    │                       │   └── UserControllerTest.java
    │                       ├── modelTest
    │                       │   ├── RoleTest.java
    │                       │   └── UserTest.java
    │                       └── setup
    │                           └── StandaloneMvcTestViewResolver.java
    └── vprofile.iml

43 directories, 90 files


