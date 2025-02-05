# How to Run This Application on Docker?

## Prerequisites

Ensure that Docker is installed on your VM or EC2 instance.

## Steps to Run the Application

1. **Pull the Docker Image**

   ```sh
   docker pull durgadockerdemo/djangodocker:latest
   ```

2. **Run the Docker Container**

   ```sh
   docker run -p 8000:8000 -it durgadockerdemo/djangodocker:latest
   ```

This will start the application and expose it on port `8000`.

Web URL: \<IP\_ADDR>:8000/demo/
