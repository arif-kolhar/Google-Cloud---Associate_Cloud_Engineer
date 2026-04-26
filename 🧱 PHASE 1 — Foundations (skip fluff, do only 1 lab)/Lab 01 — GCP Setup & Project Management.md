# Lab 01: GCP Setup & Project Management

## Objective
Set up a Google Cloud environment correctly, including project creation, billing, APIs, and default configurations. This lab ensures a solid foundation for all future labs.

---

## Prerequisites

- Google account  
- Access to Google Cloud Free Tier (or billing-enabled account)  
- Basic understanding of cloud concepts  

---

## Lab Tasks

### Task 1: Create a Google Cloud Project

1. Go to the Google Cloud Console:  
   https://console.cloud.google.com/

2. Click the **project dropdown** (top navigation bar)

3. Click **New Project**

4. Configure:
   - **Project Name:** `gcp-ace-lab-01`
   - Organization: default

5. Click **Create**

6. Select the newly created project

---

### Task 2: Enable Billing

> ⚠️ Without billing, most services will fail silently.

1. Go to **Billing**
2. Link your project to a billing account
3. Confirm billing is active

---

### Task 3: Set Default Region and Zone

```bash
gcloud config set compute/region us-central1
gcloud config set compute/zone us-central1-a
