## Helm Chart for Book Server

This Helm chart deploys a book server application on Kubernetes.

### Quick Start

1. **Install Helm:** Follow the [installation guide](https://helm.sh/docs/intro/install/).
2. **Clone the Repo:**
   ```sh
   git clone https://github.com/arnab-baishnab/Learning-Helm.git
   cd Learning-Helm/book-server-helm
3. **Install the Chart**
   helm install book-server-helm .
4. **upgrade the chart**
   helm upgrade book-server-helm .
5. **Uninstall**
   helm uninstall book-server-helm

**Configuration**
**Adjust the values.yaml file to configure:**

Image Repository and Tag
Service Type and Ports
Probes and Autoscaling
Contributing
Open issues or submit pull requests for suggestions or improvements.

