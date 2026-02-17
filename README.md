# 📘 Ansible Hands-On Practice & Playbooks

This repository contains interactive, hands-on **Ansible playbooks and examples** designed for learning automation fundamentals and real-world automation tasks.

Instead of reading theory, this repo focuses on real playbooks that teach how Ansible works step-by-step — from variables and inventory files, to loops, conditions, and real automation exercises.

---

## 🔍 What’s in This Repo

### 📂 Playbooks & Examples
- `1.Playbook.yaml` — First basic playbook example  
- `2.vars.yaml`, `3.vars.yaml`   
- Multiple `.yaml` files covering:
  - Variables
  - Conditionals
  - Loops
  - Filters
  - Gathering facts

### 📝 Supporting Files
- `inventory.ini` — Sample inventory with host groups  
- `ansible_facts.json` — Saved output of Ansible facts  
- Variable practice files (`10.vars-preference.yaml`, etc.)  
- Course examples and students list (`course.yaml`, `students.yaml`)  
- `vars/` directory containing variable files

---

## 🎯 What You’ll Learn

This repo helps you understand:
- How Ansible executes YAML playbooks  
- Inventory structure and host grouping  
- Variable precedence and usage  
- Conditional execution with `when`  
- Looping tasks using `loop` and filters  
- Gathering system facts and using them  
- Real examples that mirror beginner-to-intermediate automation scenarios

---

## 🔥 Quick Start

1. Install Ansible on your control machine  
2. Clone this repo  
```bash
git clone https://github.com/NagaAjay1812/Ansible
cd Ansible
```

3. Run an example playbook:
```bash
ansible-playbook -i inventory.ini 1.Playbook.yaml
```

---

## 📌 Why This Matters

Ansible is a simple yet powerful automation tool that lets you define infrastructure as code in YAML — readable by humans and machines alike. It’s widely used for:
- Configuration management
- Application deployment
- Inventory orchestration
- Multi-node automation

By practicing with these examples, you’ll move from:
> *“Ansible just runs commands”*  
to  
> *“Ansible defines system-desired state reliably and repeatedly.”*

---

## 🚀 Keep Practicing

This repo is meant as a **learning playground**, so feel free to:
- Modify playbooks
- Add your own examples
- Try roles and advanced patterns

Automation skills scale beyond single servers — and this repo helps build that foundation.
