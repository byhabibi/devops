# 🚀 Mini Production Server (Docker + Nginx Reverse Proxy)

This project is a mini production-like server environment built on a VPS using Docker and Nginx as reverse proxy.

## 🧱 Architecture

Internet → Nginx Reverse Proxy → Multi Docker Containers

Services running:

* Web server (Nginx container)
* API service (http-echo container)
* Monitoring service
* Reverse proxy gateway

## ⚙️ Tech Stack

* Ubuntu VPS
* Docker & Docker Compose
* Nginx Reverse Proxy
* Linux server administration
* Firewall & port management

## 🌐 Features

* Multi-container deployment using Docker Compose
* Reverse proxy routing (/ , /api , /monitor)
* Public access via VPS
* Basic production server simulation

## 📸 Running Services

* Main Web → `/`
* API → `/api`
* Monitoring → `/monitor`

## 🎯 Purpose

This project simulates a real-world DevOps environment for learning:

* Linux server management
* Container deployment
* Reverse proxy configuration
* Production-like infrastructure setup
