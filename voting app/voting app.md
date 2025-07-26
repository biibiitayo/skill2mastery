<img width="975" height="907" alt="image" src="https://github.com/user-attachments/assets/efe23ac9-b7bc-486a-9564-b64bd6333cad" />

•  Create a Docker Machine instance. Set up a new Docker Machine to host your containers.
•  SSH into the Docker Machine (Ubuntu). Connect to the Ubuntu-based Docker Machine using SSH.
•  Clone the GitHub repository. Once connected, navigate to your desired directory and run the command to clone the repository:
git clone https://github.com/your-repo-name.git

<img width="975" height="376" alt="image" src="https://github.com/user-attachments/assets/98ee5eba-043d-4c0c-a1f4-48fbb8e9316b" />


Create the Redis and Postgres application.

Create Redis and PostgreSQL containers. Use Docker to spin up Redis and PostgreSQL services for your application:

docker run -d --name redis redis
docker run -d --name db -e POSTGRES_PASSWORD=password Postgres:15-alpine


<img width="975" height="453" alt="image" src="https://github.com/user-attachments/assets/4d5c3a0e-9fcb-48f3-ba67-22d70c21ccc9" />


<img width="975" height="476" alt="image" src="https://github.com/user-attachments/assets/09ea6159-ecd7-417a-9062-6a71c7508492" />


Docker-compose up


<img width="975" height="513" alt="image" src="https://github.com/user-attachments/assets/3b18acbf-6c3c-438b-83c4-780690e35436" />

<img width="975" height="516" alt="image" src="https://github.com/user-attachments/assets/e3c7683c-d27f-4a1d-95c4-26401adb1a7c" />

<img width="975" height="308" alt="image" src="https://github.com/user-attachments/assets/59664de9-2a4e-4308-a039-c09874b8a030" />


<img width="975" height="631" alt="image" src="https://github.com/user-attachments/assets/504ba653-0ce1-4ea0-b247-1f5b25bc8c78" />

<img width="975" height="483" alt="image" src="https://github.com/user-attachments/assets/cb0ea2b3-aff2-432a-99c7-1175f48bd401" />



<img width="975" height="349" alt="image" src="https://github.com/user-attachments/assets/57d545c4-aef0-43de-92c9-7bb9883c003c" />
