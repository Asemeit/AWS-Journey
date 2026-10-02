# ☁️ AWS Journey & Builder Logs

Welcome to my hands-on Amazon Web Services (AWS) learning repository. This repository documents my step-by-step progress, architecture configurations, and technical lab reports.

---

## 📂 Repository Structure

* **`aws-builder-journal/`**
  * **`01-aws-onboarding/`**
    * **`lab-reports/`**
      * [Lab 01: Account Setup & IAM Management](./aws-builder-journal/01-aws-onboarding/lab-reports/01-account-setup-and-iam.md)
      * [Lab 02: EC2 Linux Instance Setup & Remote SSH Access](./aws-builder-journal/01-aws-onboarding/lab-reports/02-ec2-linux-ssh-connection.md)

---

## 🛠️ Security Practices
* **No Hardcoded Credentials:** AWS access keys and `.pem` key pairs are strictly excluded via `.gitignore`.
* **Key Permissions:** All SSH private keys are restricted locally using `chmod 400`.
