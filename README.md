# Docker_Ollama_Portainer-set-up
Guide for a beginner to install Docker, Ollama and Portainer for MAC

1. Make sure you have Homebrew installed.
       - Else, you can use https://brew.sh/
2. Install Docker using terminal.
       - brew install docker docker-machine. This would take a while to complete. 
3. Working with Ollama: In the terminal
     - mkdir ollama (Creates a new directory 'ollama')
     - cd ollama (makes this your current directory)
     - Open a new VS Code file and paste the code from https://github.com/open-webui/open-webui/blob/main/docker-compose.yaml, this handled the frontend (port details) of Ollama.
     - save and run using 'docker compose up' in the terminal. This will take some time to download and install.
     - You can now access Ollama on your browser at 'http://localhost:3000/auth', use the Sign-Up option to create new credentials.

4. Once you have signed in Ollama, your page would look like this
 <img width="1427" alt="image" src="https://github.com/Abin09/Docker_Ollama_Portainer-set-up/assets/31739372/4e4f686c-ec28-4ff6-b873-4bb630d739af">

5. https://ollama.com/library are the different models that are currently available in Ollama. Please be careful about the model and parameter(query running and computing capability) you want to add to your account.
6. You can add any number of models using the below screenshot. 
 <img width="1395" alt="image" src="https://github.com/Abin09/Docker_Ollama_Portainer-set-up/assets/31739372/03dbd90d-5890-481e-a21e-224a9c059c5b">

7. Downloading and Installing these models would take a while, make sure you do not exit the window.
   <img width="1373" alt="image" src="https://github.com/Abin09/Docker_Ollama_Portainer-set-up/assets/31739372/e2b1e7fa-1eef-4f63-937e-64543ae97cfa">

8. Select the model you wish to run and use the 'New Chat' feature to run your queries.

9. Portainer: is a management UI that allows you to easily manage your different Docker environments.
        - Similar to Ollama create a new directory and make it the current directory (Terminal)
        - Open VS Code, copy the code from https://github.com/docker/awesome-compose/blob/master/portainer/compose.yaml, and save it.
        - use 'docker compose up -d' to run the code.
        - Access Portainer using http://localhost:9000/#!/auth and create your login.
   <img width="1415" alt="image" src="https://github.com/Abin09/Docker_Ollama_Portainer-set-up/assets/31739372/8705755e-8555-4ad4-8b08-1a17cb3f4c05">
10. You can monitor, modify, and control your containers using the Portainer dashboard.




