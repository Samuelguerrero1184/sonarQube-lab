# sonarQube-lab

1. Run the docker image

```
docker run -d --name sonarqube -p 9000:9000 -v sonarqube_data:/opt/sonarqube/data sonarqube
```
2. Wait for the insytalation, and open de webapp with the port 9000, the defaults are admin & admin
<img width="976" alt="Captura de pantalla 2024-05-15 a las 2 04 27" src="https://github.com/Samuelguerrero1184/sonarQube-lab/assets/61643297/7dfe4677-bc45-4abe-a1a7-4b80c19cc064">

3. Once logged in, we create a project, put any name we desire and use global settings
<img width="1582" alt="Captura de pantalla 2024-05-14 a las 20 53 38" src="https://github.com/Samuelguerrero1184/sonarQube-lab/assets/61643297/d0f50873-ac6a-4e1b-a573-091e57fcdd7d">
<img width="1470" alt="Captura de pantalla 2024-05-14 a las 20 53 55" src="https://github.com/Samuelguerrero1184/sonarQube-lab/assets/61643297/3f2a60bd-063e-44cb-9197-6f440896a284">

4. Choose the analysis method, this case locally
<img width="797" alt="Captura de pantalla 2024-05-15 a las 2 08 50" src="https://github.com/Samuelguerrero1184/sonarQube-lab/assets/61643297/63e0639d-5e51-46ac-ab7c-14bf4f8678e5">

5. Provide token
<img width="1470" alt="Captura de pantalla 2024-05-14 a las 20 54 13" src="https://github.com/Samuelguerrero1184/sonarQube-lab/assets/61643297/a3f5bd12-c69e-42e9-9087-7cb864014cb3">

6. Select the type of project, your operating system and install sonar-scanner, in this case with brew
   ```
   brew install sonar-scanner
   
<img width="1470" alt="Captura de pantalla 2024-05-14 a las 20 54 27" src="https://github.com/Samuelguerrero1184/sonarQube-lab/assets/61643297/ef45c0a2-5b20-48f4-96f1-8950ce23a2e9">
<img width="1468" alt="Captura de pantalla 2024-05-14 a las 20 55 06" src="https://github.com/Samuelguerrero1184/sonarQube-lab/assets/61643297/9ffdf452-32d4-4fa1-85f5-ccf5c6b8d183">

7. Once installed we run the following command in the projects directory
<img width="487" alt="Captura de pantalla 2024-05-14 a las 20 54 36" src="https://github.com/Samuelguerrero1184/sonarQube-lab/assets/61643297/eaffec9a-f5d0-41d2-820b-323e9db221b1">
<img width="1470" alt="Captura de pantalla 2024-05-14 a las 20 55 27" src="https://github.com/Samuelguerrero1184/sonarQube-lab/assets/61643297/75259917-07ff-4a14-9c51-a15e52c0e067">

8. And finally we should get this feedback on the web interface

<img width="1470" alt="Captura de pantalla 2024-05-14 a las 20 52 53" src="https://github.com/Samuelguerrero1184/sonarQube-lab/assets/61643297/8cf544cc-d8cf-432e-8b41-ce40cf8f4402">
<img width="988" alt="Captura de pantalla 2024-05-14 a las 20 53 03" src="https://github.com/Samuelguerrero1184/sonarQube-lab/assets/61643297/752430f7-481d-4c1a-af1d-34f86ff28194">





