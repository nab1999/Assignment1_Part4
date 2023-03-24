# Assignment1_Part4

## Part 4: Docker Networking

### Step1: (Create a new Docker network named "my_network" using the bridge driver)

![image](https://user-images.githubusercontent.com/126570628/227613221-734efed1-f6cc-4680-9b7b-e1aacf083bb3.png)

### Step2: (Create a new Docker container using the "nginx" image and connect it to the "my_network" network. Name the container "nginx_container")

![image](https://user-images.githubusercontent.com/126570628/227613297-d7c392db-5f22-45a4-bd88-c10ca2c3b8e6.png)

![image](https://user-images.githubusercontent.com/126570628/227613531-5fd95192-c126-439b-ac4f-253bbceabbda.png)

### Step3: (Verify that the "nginx" default page is accessible on your host machine at http://localhost:8080)

![image](https://user-images.githubusercontent.com/126570628/227613607-d9cb07a4-397e-4195-a155-363d3503fe00.png)

### Step4: (Create a new Docker container using the "httpd" image and connect it to the "my_network" network. Name the container "httpd_container")

![image](https://user-images.githubusercontent.com/126570628/227613674-e60837c1-f4e7-45b7-a2c3-51cffbe48ecc.png)

### Step5: (Verify that the "httpd" default page is accessible on your host machine at http://localhost:8081)

![image](https://user-images.githubusercontent.com/126570628/227613750-ee9e34b4-96ac-494c-89b5-17d4fd9b6ca8.png)

### Step6: (Use the "docker network inspect" command to display information about the "my_network" network. Document your findings in the README.md file)

![image](https://user-images.githubusercontent.com/126570628/227613817-bef35e49-13aa-4602-8e1f-9579f6136683.png)

### Step7: (Stop and remove the "nginx_container" container)

![image](https://user-images.githubusercontent.com/126570628/227613971-98f532ff-eda9-4e72-9790-571cce0deb4d.png)

### Step8: (Create a new Docker container using the "nginx" image and connect it to the "my_network" network. Name the container "nginx_container_2")

![image](https://user-images.githubusercontent.com/126570628/227614145-7bb86609-ee30-4f16-b2fe-121036e1e2ad.png)

### Step9: (Verify that the "nginx" default page is accessible on your host machine at http://localhost:8082)

![image](https://user-images.githubusercontent.com/126570628/227614237-fd47b208-bbb9-4a5f-a846-831c22188484.png)

### Step10: (Use the "docker container ls" command to display information about all running containers. Document your findings in the README.md file)

![image](https://user-images.githubusercontent.com/126570628/227614298-6ed6dab7-dc9f-4e6a-a144-7520f7813988.png)

### Step11: (Stop and remove all containers)

![image](https://user-images.githubusercontent.com/126570628/227614345-abb36e73-ceff-46e7-bfbe-969d28d6a6d9.png)

### Step12: (Cleanup: Remove the "my_network" network)

![image](https://user-images.githubusercontent.com/126570628/227614384-240ce5d6-306a-4366-9fd0-bd205f24ad93.png)

### Step13: (Create a README.md file)

Created a README.md file in “Assignment1_Part4” GitHub repository under the main branch. This file contains the findings for each command used in Part 4 of the assignment.

### Step14: (Push the codebase for the sample application to your GitHub repository)

Initializing git in “assignment1_part4” directory, and then committing the sample application files to local repository.

![image](https://user-images.githubusercontent.com/126570628/227614592-d348eefd-c240-4c59-9d6d-92258a6bae7d.png)

Then we pushed the codebase for the sample flask application to the GitHub repository under master branch by first setting the remote repository configuration: “git remote add origin https://github.com/nab1999/Assignment1_Part4.git” and then pushing the local git repository to remote/central/GitHub repository by using the command: “git push -u origin master”. To verify that is has been pushed successfully we can check the files in the GitHub repository in the browser. And to pull the files/repository to our local machine/repository, we used the command “git pull -u origin master”.

![image](https://user-images.githubusercontent.com/126570628/227614671-bb35d705-3bb4-4e84-b2bb-daf107109e01.png)

![image](https://user-images.githubusercontent.com/126570628/227614707-be424b90-a3fd-4826-895d-7b319cecc605.png)
