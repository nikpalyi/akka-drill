
## Instructions and Navigation
All of the code is organized into folders. Each folder starts with a number followed by the application name. For example, Chapter 06.

The code will look like the following:

        package com.packt.chapter6
         sealed trait UserAction
         case object Add extends UserAction
         case object Remove extends UserAction
         case class UserUpdate(userId: String, action: UserAction)
         sealed trait Event
         case class AddUserEvent(userId: String) extends Event
         case class RemoveUserEvent(userId: String) extends Event
         
### Software requirements:
| __Chapter number__ | **Software required (With version)** | **Free/Proprietary** | **If proprietary, can code testing be performed using a trial version** | **If proprietary, then cost of the software** | **Download links to the software** | __Hardware specifications__ | **OS required** |
|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|
| All | SBT 0.13.13 | Free | No |  | http://www.scala-sbt.org/ | No hardware specifications. | Windows,Linux,Mac OS |
 
#### Detailed installation steps (software-wise)
The steps should be listed in a way that it prepares the system environment to be able to test the codes of the book.

SBT:

Download latest package from http://www.scala-sbt.org/download.html

Install package

Run sbt “sbt sbtVersion” in the command line to test the software was installed correctly.
    
### Note:
The Code folder contains the code samples used in this book.

Code bundle for Chapter 1 to 5 is present in the "Hello-akka" folder.

Software_Hardware_list file contains the list of required software and hardware for this book.

Happy coding! :)

## Related Products:
* [Apache Kafka Cookbook](https://www.packtpub.com/big-data-and-business-intelligence/apache-kafka-cookbook?utm_source=github&utm_medium=repository&utm_content=9781785882449)

* [Building Microservice with AKKA HTTP [Video]](https://www.packtpub.com/application-development/building-microservice-akka-http-video?utm_source=github&utm_medium=repository&utm_content=9781788298582)

* [Mastering Akka](https://www.packtpub.com/application-development/mastering-akka?utm_source=github&utm_medium=repository&utm_content=9781786465023)

### Download a free PDF

 <i>If you have already purchased a print or Kindle version of this book, you can get a DRM-free PDF version at no cost.<br>Simply click on the link to claim your free PDF.</i>
<p align="center"> <a href="https://packt.link/free-ebook/9781785288180">https://packt.link/free-ebook/9781785288180 </a> </p>
