
# 🚀 Terraform Docker NGINX Container

This project demonstrates Infrastructure as Code (IaC) using **Terraform** to provision a local **NGINX container** using the **Docker provider**.

---

## 📦 Project Structure

```bash
.
├── main.tf                  # Terraform configuration file
├── terraform.tfstate        # Terraform state file
├── terraform.tfstate.backup # Backup state file
├── .terraform.lock.hcl      # Provider lock file
├── logs/                    # Execution logs
│   ├── init.log
│   ├── plan.log
│   ├── apply.log
│   ├── destroy.log
│   └── state-list.log
└── 2025-08-07\_19-25.png     # Screenshot of the container running
````

---

## 🎯 Objective

Provision a Docker container using Terraform to demonstrate local containerized infrastructure provisioning with IaC principles.

---

## 🛠️ Tools Used

* [Terraform](https://www.terraform.io/) - Infrastructure as Code tool
* [Docker](https://www.docker.com/) - Container platform
* Terraform Docker Provider

---

## ✅ Tasks Completed

* [x] Used Docker provider in Terraform
* [x] Wrote `main.tf` to create an NGINX container
* [x] Ran `terraform init`, `terraform plan`, and `terraform apply`
* [x] Verified container using `docker ps`
* [x] Destroyed infrastructure with `terraform destroy`
* [x] Checked state with `terraform state list`
* [x] Saved all logs in `logs/` directory

---


## 📂 Logs

All logs from `init`, `plan`, `apply`, `state`, and `destroy` commands are saved in the `logs/` folder for review and submission.

