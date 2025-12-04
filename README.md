TASK 1  Dockerization
- Implemented multi-stage Dockerfiles for backend (Spring Boot + Maven) and frontend (React).
- `docker-compose.yml` runs backend, frontend, and Postgres together.  
Screenshot showing all containers running (docker ps)  
<img width="1918" height="1016" alt="Screenshot 2025-12-02 170741" src="https://github.com/user-attachments/assets/03256e96-bdad-4b14-a800-0539cea9468e" />  
TASK 2  CI/CD with Jenkins  
- Level-1: Basic pipeline in Jenkins UI (Checkout + Backend build).  
- Level-2: Declarative Jenkinsfile with stages: Checkout, Build, Docker Build, Docker Push.  
- Level-3: Jenkins shared library.  
Screenshot showing all Jenkins UI job execution and build logs  
<img width="1917" height="1011" alt="Screenshot 2025-12-02 223450" src="https://github.com/user-attachments/assets/2ac83b6a-5fd0-4d12-b4f7-acb60bcffd27" />
<img width="1919" height="1017" alt="Screenshot 2025-12-02 223522" src="https://github.com/user-attachments/assets/12c92f0d-470a-4f62-ae7e-e8fcf5d0e599" />  
Screenshot showing all Declarative Jenkins job execution and build logs  
<img width="1914" height="1017" alt="Screenshot 2025-12-02 234647" src="https://github.com/user-attachments/assets/51885290-97c2-4155-9659-8392c4aee226" />
<img width="1919" height="1016" alt="Screenshot 2025-12-02 234707" src="https://github.com/user-attachments/assets/f6eb0e0f-6314-42dc-91ba-a34e36d4210a" />  
TASK 3  Kubernetes Deployment  
- Raw YAML for backend, frontend, and Postgres.  
- Helm chart YAML files.  
Screenshot showing all pods and services running
<img width="1919" height="1007" alt="Screenshot 2025-12-03 143206" src="https://github.com/user-attachments/assets/5c3ea432-c02a-4cbd-9fd0-8b30dc922f7a" />  
TASK 4  Database Integration  
- Deploy Postgres using plain YAML files (Deployment + Service). Credentials can be stored in the configuration directly for understanding (not secure).  
Screenshot showing backend and frontend Helm charts successfully deployed  
<img width="1909" height="1016" alt="Screenshot 2025-12-03 150648" src="https://github.com/user-attachments/assets/9f6cd831-6b0a-46cf-af87-50767ac67607" />  
Screenshot showing pods are running
<img width="1919" height="963" alt="Screenshot 2025-12-03 150755" src="https://github.com/user-attachments/assets/7fd9e444-12d2-4cb6-9a67-8cc24e3a4aa5" />  
Screenshot showing successful backend to DB connection logs  
<img width="1918" height="1019" alt="Screenshot 2025-12-03 171621" src="https://github.com/user-attachments/assets/6fb80cfa-7547-4e4b-8c74-f6c53d6b54a5" />  
TASK 5  Monitoring  
Deploy Prometheus and Grafana using Helm charts. Ensure both pods are running and accessible.   
Screenshot showing Prometheus UI  
<img width="1919" height="1022" alt="Screenshot 2025-12-03 183321" src="https://github.com/user-attachments/assets/fa9e2ce0-a639-438f-b758-a4d3bf026f10" />  
Screenshot showing Grafana UI  
<img width="1919" height="1014" alt="Screenshot 2025-12-03 183731" src="https://github.com/user-attachments/assets/8fafe14e-5af1-4c16-a3de-38dae0151c81" />  
<img width="1917" height="1015" alt="Screenshot 2025-12-04 001419" src="https://github.com/user-attachments/assets/d47b1b30-4f19-44a5-bd14-7a1df5407eb9" />  
TASK 6  Infrastructure as Code (Terraform)  
Write Terraform scripts to create basic AWS resources like an S3 bucket or EC2 instance. Understand Terraform workflow (init, plan, apply).
Build a VPC setup with EC2 instance, Internet Gateway, and Security Groups using Terraform modules and variables.
<img width="1914" height="1019" alt="Screenshot 2025-12-04 005346" src="https://github.com/user-attachments/assets/f5518853-630e-45ec-97c4-d8ff76f9294d" />
<img width="1919" height="1017" alt="Screenshot 2025-12-04 003906" src="https://github.com/user-attachments/assets/b5647403-8a66-46a0-a430-16b6680a0d74" />
<img width="1884" height="879" alt="Screenshot 2025-12-04 004033" src="https://github.com/user-attachments/assets/b6591738-67e4-42b1-853f-4cdaa16c3689" />
<img width="1910" height="967" alt="Screenshot 2025-12-04 011410" src="https://github.com/user-attachments/assets/451692da-a7e7-461c-8ee7-6b080ef9582b" />
<img width="1914" height="778" alt="Screenshot 2025-12-04 011435" src="https://github.com/user-attachments/assets/8370c306-e3d1-4fc5-b974-2d55033f4197" />
<img width="1918" height="827" alt="Screenshot 2025-12-04 011444" src="https://github.com/user-attachments/assets/2cb5b543-1b00-45a0-8f66-36d748bfbbe4" />
<img width="1919" height="865" alt="Screenshot 2025-12-04 011453" src="https://github.com/user-attachments/assets/6fbff417-18f4-4455-a4f1-f59986aa2ec1" />
<img width="1919" height="866" alt="Screenshot 2025-12-04 011501" src="https://github.com/user-attachments/assets/120407fa-3590-4126-a3a8-afa0ae89639e" />
<img width="1919" height="793" alt="Screenshot 2025-12-04 011558" src="https://github.com/user-attachments/assets/6e66f56f-ea49-4919-a9fa-2b0372015a09" />
