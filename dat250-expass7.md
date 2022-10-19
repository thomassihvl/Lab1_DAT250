# DAT250 Expass 7

# Experiment 1: Installation
Went fine following the installation guide with Chocolatey.

## Experiment 2: Hello World
I followed the tutorial and everything went fine until it was time to compile Sender and Recv with 
´javac -cp amqp-client-5.7.1.jar Send.java Recv.java´. 

I got a long error message saying that my classes didn't exist. I guess it has something to do with me using Maven instead of .JAR files, but I skipped this step as it took too long to find a solution myself with limited Java knowledge and it didn't seem important, but came back to it later when I found out it was important after all...

## Experiment 3: Work Queue
This experiment also went fine until I had to schedule tasks with compiled .jar-files. I had to go back to Experiment 1 and solve the problem. After re-reading the tutorial I found a box with information about the Java client library, instructing me to dowload the .jar files manually and put them in my working directory. I also had to change the commands a bit to work with Windows CMD. The rest of the experiment went ok, with only small hickups. However I noticed that some messages were lost. They weren't saved in a queue either. I think it was because I didn't have the reciever Terminal window selected, as the Work Queue test numbered messages eventually came through after I had clicked all the terminal windows.

## Experiment 4: Topics
This part went smooth.


<b>Link to GitHub repo [here](https://github.com/thomassihvl/dat250-expass7/tree/main/RabbitMQHelloWorld).
