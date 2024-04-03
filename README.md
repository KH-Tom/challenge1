Challenge 1: Serving Static Content with NGINX
The first challenge involved deploying static web content using Docker and NGINX, a seemingly straightforward task that introduced me to the complexities of Docker configurations and web server setup.
Encountered Issues and Resolutions
•	Dockerfile Misnaming: Initially, my Dockerfile was mistakenly named Dockerfile.txt, which prevented Docker from locating it. This mistake highlighted the importance of precise file naming conventions in Docker's operation.
•	Port Binding Error: When I encountered the error "Bind for 0.0.0.0:8080 failed: port is already allocated," I learned to check for port conflicts and the significance of managing system resources carefully, ensuring no two services compete for the same port.
Key Learnings
•	Docker Basics: Gained hands-on experience with Docker commands and the significance of correctly naming and placing the Dockerfile.
•	Web Server Configuration: Understood the basics of setting up NGINX to serve static content, diving into NGINX's configuration and how it interprets and serves web pages.
Display My name and student ID: http://localhost:8080
