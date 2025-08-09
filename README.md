# Full-Stack-Deployment-using-Ansible

🌐Full Stack Deployment using Ansible. This project is a real-world demonstration of how you can deploy a complete full-stack web application on AWS using Ansible automation. The project separates the application into three different layers — Frontend, Backend, and Database — each hosted on its own EC2 instance. Everything is provisioned and configured automatically using Ansible playbooks, which makes it a production-style project with DevOps practices.

🔧 How the Project Works — Step by Step Three EC2 instances are launched:

One each for frontend, backend, and database.

Each instance is listed in an Ansible inventory file (hosts.ini).

A main playbook (site.yml) is run from the Ansible controller to configure all layers.

Each component is automated using its own playbook:

frontend.yml: Installs Nginx and deploys a beautiful HTML+CSS page.

backend.yml: Installs Node.js, clones a GitHub app, and runs it.

database.yml: Installs MariaDB, creates a database and user, and configures access.

✅ What’s Special About This Project? 🔁 Fully Automated: Just one command deploys the whole app.

🌍 Cloud-Based: Uses AWS EC2 to simulate real-world deployment.

📂 Structured: Clean folder structure, clear roles, and readable code.

💡 Educational: Great for learning Ansible, Linux, cloud, and DevOps all at once.

🎨 Visually Clean UI: Includes a stylish frontend that confirms all services are working.

🧾 Technologies Used Ansible – for automation

AWS EC2 – cloud infrastructure

Nginx – frontend server

Node.js + Express – backend logic

MariaDB – database

HTML + CSS – user interface

🎯 Final Result Once deployed, visit your frontend server's public IP in a browser. You’ll see:

🚀 JD's Full Stack App Deployed with Ansible! Everything is working perfectly 🎯 ✅ Frontend | ✅ Backend | ✅ Database


ScreenShots:
![Uploading Screenshot 2025-08-08 233128.png…]()

