# docker-nodejs-project

1. Write dockerfile defining base image, update/install dependencies, set WORKDIR and copy package.json and other files to it, run npn install, expose port and provide CMD to start npm for node app

![image](https://github.com/user-attachments/assets/9027738b-fd60-4dee-af9c-f6206a3d9776)

2. Write simple app.js

![image](https://github.com/user-attachments/assets/9ea34348-2197-41b4-aee5-e682dc4ebf20)

3. Write one package.json file

![image](https://github.com/user-attachments/assets/1de07b12-58ee-41f5-96d5-a0b070f4e21c)

4. Now build and run the container

Build :- **docker build -t nodejs-app .**

Run :- **docker run -p 3000:3000 nodejs-app**

![image](https://github.com/user-attachments/assets/0a139492-7608-44e4-9019-5333114efdfc)

![image](https://github.com/user-attachments/assets/2dbe355b-796c-4c9a-856c-4da75015b908)

![image](https://github.com/user-attachments/assets/89145140-e1b0-4671-9219-b3e0199ac5cb)

5. To access application :- http://localhost:3001

![image](https://github.com/user-attachments/assets/36340357-576c-4aa6-8226-c1b624126d97)
![image](https://github.com/user-attachments/assets/9fb25470-ee34-4a82-ba9a-3df6d15069bf)
