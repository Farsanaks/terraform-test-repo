# Terraform AWS EC2 Project

## Overview

This project demonstrates how to provision an EC2 instance on AWS using Terraform. It uses Infrastructure as Code (IaC) principles to automate cloud resource creation.

---

## Features

* Provision EC2 instance using Terraform
* Automatically fetch latest Amazon Linux AMI
* Simple and minimal configuration
* Easy to extend for advanced use cases

---

## Technologies Used

* Terraform
* AWS (EC2)
* Git & GitHub

---

## Project Structure

```
.
├── main.tf
├── README.md
└── .gitignore
```

---

## Prerequisites

* AWS account
* AWS CLI configured
* Terraform installed

---

## How to Run

### 1. Clone the repository

```
git clone https://github.com/your-username/your-repo.git
cd your-repo
```

### 2. Initialize Terraform

```
terraform init
```

### 3. Preview changes

```
terraform plan
```

### 4. Apply configuration

```
terraform apply
```

---

##  Output

After successful execution, Terraform will create an EC2 instance in AWS.

---

##  Cleanup

To avoid unnecessary charges:

```
terraform destroy
```

---

##  Learning Outcome

* Understanding Terraform basics
* Working with AWS EC2
* Using Infrastructure as Code

---

# terraform-test-repo
