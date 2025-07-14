# Privorion — Privacy‑First Federated Learning Platform for Edge Computing

Privorion is an open‑source demonstrator designed to showcase how federated learning with differential privacy (DP) can be orchestrated across hierarchical edge environments using production‑grade tech stacks.

## ✨ Highlights
* Federated Learning with Differential Privacy - Leverages FlowerAI to conduct secure, privacy-preserving model training across multiple simulated edge tiers, while balancing performance and privacy.
* Scalable, Cloud‑Native Architecture - Built with React (UI), Node.js (controller), Python (ML middleware), PostgreSQL (data store), and RabbitMQ + KEDA on Kubernetes for robust task orchestration and autoscaling.
* Hierarchical Edge Simulation - Models industrial scenarios by grouping edge devices into tiers (e.g., regional/local), enabling federated aggregation both within edge groups and globally.
* Async Communication & Autoscaling - Uses RabbitMQ to decouple UI/controller from Python middleware; KEDA monitors queue depth to dynamically scale worker pods.
* Role-Based Authorization - Integrates GitHub OAuth with three distinct roles—Super Admin, Admin, Operator—for secure multi-user access control.

## 🎯 Objectives
* Provide a realisable blueprint for building enterprise-grade FL+DP systems.
* Demonstrate trade-offs between model accuracy and privacy (configurable ε/δ).
* Showcase Kubernetes-native ops, including secure authentication, messaging, and scaling.
* Serve as an educational tool for researchers, practitioners, and students to explore hierarchical federated learning.

## ✅ Ideal For
* Developers exploring privacy-first distributed ML.
* Organizations evaluating edge/industrial AI architectures.
* Educators teaching federated learning, distributed privacy, cloud-native, and microservices.
