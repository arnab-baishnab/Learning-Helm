Helm Chart for Book Server
This repository contains a Helm chart for deploying a book server application on Kubernetes. Helm is a package manager for Kubernetes that helps you manage complex applications with ease.

Features
Templates: Simplifies the creation and management of Kubernetes manifests using Go templating.
Configuration: Easily configurable via the values.yaml file, allowing you to customize settings like image tags, replica counts, and service types.
Deployment: Supports standard Helm commands for installing, upgrading, and managing your application.
Getting Started
Install Helm: Follow the official Helm installation guide to set up Helm on your local machine.

Clone the Repository:

sh
Copy code
git clone https://github.com/arnab-baishnab/Learning-Helm.git
cd Learning-Helm/book-server-helm
Install the Chart:

sh
Copy code
helm install book-server-helm .
Upgrade the Chart:

sh
Copy code
helm upgrade book-server-helm .
Uninstall the Chart:

sh
Copy code
helm uninstall book-server-helm
Configuration
Modify the values.yaml file to adjust configurations such as:

Image Repository and Tag
Service Type and Ports
Probes and Autoscaling
Contributing
Feel free to open issues or submit pull requests if you have suggestions or improvements.

License
This project is licensed under the MIT License. See the LICENSE file for details.
