# Esteban Martins

Infrastructure and backend engineer. Background in networking (TCP/IP, VLANs,
enterprise wireless); now focused on containerized deployments, cloud infrastructure,
and automation.

---

## Stack

**Infrastructure & operations**
Docker · Docker Compose · Nginx · Linux (Ubuntu) · Let's Encrypt · GitHub Actions CI/CD

**Cloud — AWS**
EC2 · S3 · SES · DynamoDB · VPC · IAM · Elastic IP · Terraform (HCL)

**Backend**
Python · Django · Django REST Framework · Flask · Gunicorn · PostgreSQL

**Networking** *(background)*
TCP/IP · DNS · VLANs · Meraki · Ruckus · UniFi · firewall configuration

---

## Projects

### [nginx-flask-prod](https://github.com/hokuto06/nginx-flask-prod)
Multi-service production stack on a single EC2 instance. Nginx reverse proxy handles
TLS termination for multiple virtual hosts; services deployed via Docker Compose.

- **django-api** — REST API with JWT auth, S3 media storage, PostgreSQL backend
- **blog-front** — Django template frontend consuming the API
- **flask** — landing page with SES email pipeline and DynamoDB inbox
- **certbot** — automated Let's Encrypt renewal via shared bind-mount volume
- CI/CD via GitHub Actions: commit-tag driven restart/rebuild over SSH

### [aws-infra](https://github.com/hokuto06/aws-infra)
Terraform-managed AWS production environment.

- VPC with public/private subnets, route tables, and standardized tagging
- EC2 instance with Elastic IP and IAM instance profile for DynamoDB access
- Infrastructure state tracked and reproducible

### [iot-rpi](https://github.com/hokuto06/iot-rpi)
Home automation stack on a Raspberry Pi 4.

- Home Assistant core with Zigbee2MQTT (USB coordinator), local Mosquitto broker
- Nginx TLS proxy, Sonoff/Tuya/Alexa integrations, evapotranspiration irrigation scheduler
- Fully containerized via Docker Compose

### [myscripts](https://github.com/hokuto06/myscripts)
Python tooling for enterprise network operations — Meraki, Ruckus, UniFi API automation,
bulk device configuration, and Excel report generation.

---

## Contact

[estebanmartins.com.ar](https://estebanmartins.com.ar) · [LinkedIn](https://www.linkedin.com/in/esteban-martins-816b9837/)
