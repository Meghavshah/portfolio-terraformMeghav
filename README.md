This repository contains my personal Cloud Engineer portfolio, built with HTML and CSS and deployed to Google Cloud using Terraform. It uses **Google Cloud Storage** to host the static site.

---

## 📦 Project Structure

```

portfolio-terraformMeghav/
├── index.html
├── styles.css
├── profile.jpg
├── main.tf
├── variables.tf
├── outputs.tf
└── README.md

````

---

## 🌐 What You'll Deploy

- A static website hosted on a GCP Storage bucket
- Provisioned using Terraform
---

## ⚙️ Prerequisites

Before you begin:

- [Google Cloud SDK installed](https://cloud.google.com/sdk/docs/install)
- [Terraform installed](https://developer.hashicorp.com/terraform/downloads)
- A Google Cloud project with billing enabled

---

## 🔐 Authenticate with GCP

Use Application Default Credentials:

```bash
gcloud auth application-default login
gcloud config set project YOUR_PROJECT_ID
````

---

## 🧱 Terraform Setup

### 1. Initialize Terraform

```bash
terraform init
```

### 2. Review the execution plan

```bash
terraform plan
```

### 3. Apply to create resources

```bash
terraform apply
```

Type `yes` when prompted.

---

