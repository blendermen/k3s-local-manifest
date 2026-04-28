# k3s-local-manifest


# 🚀 K3S DevOps Project: React, Flask & PostgreSQL

A comprehensive full-stack application ecosystem deployed on **local K3S/K3D**


<img width="1329" height="910" alt="k3sdemo" src="https://github.com/user-attachments/assets/de1924ef-ac19-4a68-8692-47dbfcaaec51" />


<img width="1507" height="768" alt="argocd" src="https://github.com/user-attachments/assets/d927428b-7f96-4225-a054-2976edae6484" />



## 🏗️ System Architecture

The application consists of **three** tiers running within the Kubernetes cluster:

* **Frontend:** React (Vite) application served via Nginx.
* **Backend:** REST API built with Flask (Python), handling the visit counter logic.
* **Database:** PostgreSQL 15 instance with persistent storage 

This project uses **two** separate environments: **Development** and **Production**.

🔄 How it works
More info on the main app repo [k3s-local-app](https://github.com/blendermen/k3s-local-app) 