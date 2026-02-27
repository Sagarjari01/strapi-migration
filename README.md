# Strapi v4 to v5 Migration Task

This repository demonstrates the initialization, configuration, and successful major-version migration of a Strapi headless CMS project using a PostgreSQL database. 

## 🌿 Git Branching Strategy

This project is separated into two distinct branches to clearly demonstrate the migration progression:
* `main`: Contains the base Strapi v4 installation and the initial configuration of the custom Content Types (Single and Collection).
* `migrate-to-v5`: Contains the finalized codebase after successfully running the codemods and upgrading the system to Strapi v5.

## 🛠️ Tech Stack
* **Node.js**
* **Strapi** (v4 -> v5)
* **PostgreSQL**

## 📋 Prerequisites
Before running this project, ensure you have the following installed on your local machine:
* Node.js (v18 or higher recommended)
* PostgreSQL running locally

## 🚀 Local Setup Instructions

**1. Clone the repository and checkout the desired branch**
```bash
git clone <your-repo-url>
cd <your-repo-folder>

# To view the final v5 migration:
git checkout migrate-to-v5