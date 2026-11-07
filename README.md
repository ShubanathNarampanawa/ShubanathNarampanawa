# 👨‍💻 Shubanath Narampanawa

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=23&duration=3000&pause=1000&color=00D9FF&center=true&vCenter=true&width=750&lines=AI+Engineer+%7C+Software+Developer;Cybersecurity+Enthusiast;Building+Intelligent+%26+Secure+Systems" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/AI-Focused-00D9FF?style=for-the-badge" />
  <img src="https://img.shields.io/badge/AI%20%26%20Cybersecurity-Explorer-8A2BE2?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Building-The%20Future-00C853?style=for-the-badge" />
</p>

---

## 💻 `$ whoami`

```python
class Developer:
    def __init__(self):
        self.name = "Shubanath Narampanawa"
        self.role = "AI Security Engineer & Software Developer"
        self.focus = ["Artificial Intelligence", "Cybersecurity"]
        self.mindset = "Learn, Build, Secure, Innovate"

    def introduce(self):
        return "Building intelligent and secure digital solutions."

me = Developer()
print(me.introduce())
```

## 🚀 About Me

I'm an IT undergraduate specializing in **Artificial Intelligence**, passionate about building intelligent, secure, and scalable software solutions.

My interests include:

- 🤖 Artificial Intelligence & Machine Learning
- 🔐 AI-Driven Cybersecurity & AI Security
- 🛡️ Secure Software Engineering
- 🌐 Backend Engineering & Full-Stack Development
- ☁️ Cloud Security & DevSecOps
- 🧠 AI Agents and Autonomous Systems

I enjoy exploring emerging technologies, solving real-world problems, and transforming innovative ideas into practical software solutions.

## 🎓 Education

- 🎓 **BSc (Hons) in Information Technology – Artificial Intelligence**  
  University of ICBT, Sri Lanka

- 📘 **Professional Diploma in Software Engineering**  
  FQ-UK

---

## 🛠️ Tech Stack & Engineering Skills

### 💻 Programming Languages

```python
# Python - AI Development
prediction = model.predict(input_data)
```

```java
// Java - Application Development
System.out.println("Building Secure Applications");
```

```javascript
// JavaScript - API Integration
fetch("/api/agents").then(res => res.json());
```

```cpp
// C++ - Data Processing
int process(int data) { return data * 2; }
```

```bash
# Bash - Linux Automation
echo "Starting Security Scan"
```

```powershell
# PowerShell - System Management
Get-Process | Select-Object ProcessName
```

```ballerina
// Ballerina - REST API
service /agents on new http:Listener(8080) {
    resource function get .() returns json {
        return {message: "Agent API Running"};
    }
}
```

### 🤖 Artificial Intelligence & Machine Learning

```python
# PyTorch
output = torch_model(input_tensor)
```

```python
# TensorFlow
predictions = tf_model.predict(X_test)
```

```python
# OpenCV
image = cv2.imread("image.jpg")
```

```python
# Scikit-learn
model.fit(X_train, y_train)
```

```bash
# Anaconda
conda create -n ai-env python=3.11
conda activate ai-env
```

```python
# ONNX Runtime
session = ort.InferenceSession("model.onnx")
```

```python
# MLflow
mlflow.log_param("model", "RandomForest")
mlflow.log_metric("accuracy", 0.95)
```

```python
# MLOps - Model Monitoring
if model_accuracy < 0.90:
    print("Model performance alert!")
```

### 🔐 Cybersecurity & AI Security

```bash
# Kali Linux - Network Discovery
nmap -sV 192.168.1.1
```

```bash
# Linux - Firewall Status
sudo ufw status
```

```python
# OWASP LLM Security - Input Validation
if "ignore previous instructions" in user_input.lower():
    reject_request()
```

```python
# Adversarial ML - ART Toolbox
attack = FastGradientMethod(estimator=classifier, eps=0.2)
```

```bash
# Wireshark - Traffic Analysis
tshark -i eth0 -Y "dns"
```

```python
# Scapy - Packet Analysis
packets = sniff(count=10)
```

### ☁️ Cloud Security, SIEM & Analytics

```python
# AWS - S3
s3 = boto3.client("s3")
s3.list_buckets()
```

```bash
# Azure CLI
az account show
```

```python
# AWS Security - IAM
iam = boto3.client("iam")
iam.get_account_summary()
```

```kusto
// Azure Sentinel - Security Events
SecurityEvent
| where EventID == 4625
```

```json
// Elastic / ELK Stack - Log Search
{
  "query": {
    "match": {
      "event.category": "authentication"
    }
  }
}
```

```spl
# Splunk SIEM - Failed Login Detection
index=security action=failure
| stats count by src_ip
```

### 🚀 Backend Engineering, APIs & DevSecOps

```java
// Spring Boot - REST API
@GetMapping("/agents")
public String getAgents() {
    return "AI Agents";
}
```

```javascript
// Node.js - API Endpoint
app.get("/api", (req, res) => {
    res.json({ status: "running" });
});
```

```python
# FastAPI - API Endpoint
@app.get("/agents")
def get_agents():
    return {"status": "authorized"}
```

```python
# Flask - REST API
@app.route("/health")
def health():
    return {"status": "healthy"}
```

```dockerfile
# Docker - Application Container
FROM python:3.11
WORKDIR /app
COPY . .
CMD ["python", "app.py"]
```

```yaml
# Kubernetes - Deployment
apiVersion: apps/v1
kind: Deployment
metadata:
  name: ai-agent
spec:
  replicas: 2
```

```hcl
# Terraform - Cloud Infrastructure
resource "aws_s3_bucket" "data" {
  bucket = "ai-agent-data"
}
```

```yaml
# GitHub Actions - CI Workflow
name: Build
on: [push]
jobs:
  test:
    runs-on: ubuntu-latest
```

```yaml
# WSO2 API Manager - API Configuration
name: Agent API
version: v1
context: /agents
```

```json
// WSO2 Identity Server - OAuth2
{
  "grant_type": "client_credentials",
  "scope": "agent:read"
}
```

```xml
<!-- WSO2 Micro Integrator - API Integration -->
<api xmlns="http://ws.apache.org/ns/synapse"
     name="AgentAPI" context="/agents">
    <resource methods="GET">
        <inSequence>
            <send>
                <endpoint>
                    <http uri-template="http://localhost:8081/agents"/>
                </endpoint>
            </send>
        </inSequence>
    </resource>
</api>
```

### 🗄️ Databases & Data Management

```sql
-- PostgreSQL
SELECT * FROM agents
WHERE status = 'active';
```

```sql
-- MySQL
SELECT username, role
FROM users
WHERE role = 'admin';
```

```javascript
// MongoDB
db.agents.find({ status: "active" });
```

### 🧰 Development Tools & Platforms

```bash
# Git - Version Control
git add .
git commit -m "Add AI security features"
git push origin main
```

```yaml
# GitHub - Workflow
name: AI Security Project
on: [push, pull_request]
```

```json
// VS Code - Editor Settings
{
  "editor.formatOnSave": true,
  "editor.tabSize": 4
}
```

```json
// Visual Studio - Build Configuration
{
  "configurations": [
    {
      "name": "Debug",
      "configurationType": "Debug"
    }
  ]
}
```

```http
# Postman - API Testing
GET http://localhost:8000/agents
Authorization: Bearer <access_token>
```

```bash
# Linux - Development Environment
sudo apt update
sudo apt install git python3 docker.io
```

---

## 🌟 Featured Development Areas

- 🤖 **AI & Machine Learning:** Developing intelligent applications and machine learning solutions.
- 🔐 **AI Security:** Exploring AI-driven cybersecurity, LLM security, and adversarial machine learning.
- 🧩 **AI Agent Systems:** Building secure identity, authentication, and access-control solutions for autonomous AI agents.
- 🌐 **Backend Engineering:** Designing scalable APIs and secure backend architectures.
- ☁️ **Cloud & DevSecOps:** Exploring cloud infrastructure, automation, and security monitoring.

```html
<a href="https://github.com/ShubanathNarampanawa?tab=repositories">
    View My Projects
</a>
```


## 🧠 Engineering Philosophy

```python
principles = {
    "design": "Think before coding",
    "development": "Build with purpose",
    "security": "Security by design",
    "learning": "Never stop learning",
    "innovation": "Turn ideas into solutions"
}
```

- Build solutions that solve real-world problems.
- Write clean, maintainable, and scalable code.
- Integrate security into every stage of development.
- Continuously explore emerging technologies.
- Focus on learning through practical projects.

---

## 🤝 Open to Collaboration

I'm interested in collaborating on projects related to:

- Artificial Intelligence & Machine Learning
- AI Agent Development and Security
- Cybersecurity & Secure Software Engineering
- Backend Development and API Engineering
- Open-Source Projects

Feel free to connect and share innovative ideas!

## 🌍 Languages

- Sinhala
- English

---

## 📫 Connect With Me

<p align="center">
  <a href="https://github.com/ShubanathNarampanawa">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
  </a>
  <a href="https://www.linkedin.com/in/shubanath-narampanawa-67a991313">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="https://www.instagram.com/migara_narampanawa">
    <img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" />
  </a>
  <a href="mailto:cadobs92@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
  <a href="https://yourportfolio.com">
    <img src="https://img.shields.io/badge/Portfolio-00D9FF?style=for-the-badge&logo=googlechrome&logoColor=white" />
  </a>
</p>

---

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=18&duration=3000&pause=1000&color=00D9FF&center=true&vCenter=true&width=650&lines=Keep+Learning.;Keep+Building.;Keep+Innovating.;Build+Intelligent+%26+Secure+Systems." />
</p>
