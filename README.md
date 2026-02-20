# Full-Stack Banking API Integration

## Overview

This project demonstrates a **full-stack banking API integration system** built with live REST API integration into the Bank of Georgia sandbox environment.

The system functions as a **merchant-side payment gateway**, enabling secure transaction processing between a commercial frontend (e-commerce interface) and a banking infrastructure.

An online grocery store is used as the real-world use case to demonstrate:

- Payment session creation
- Transaction request validation
- Bank API communication
- Order confirmation flow
- Delivery service coordination

The project showcases full-stack architecture, backend orchestration, and third-party API integration.

---

## System Architecture

User
→
Frontend (HTML / CSS / JavaScript)
→
Express Backend (Node.js)
→
Bank of Georgia Payments API (Sandbox)
→
Transaction Confirmation
→
Order Processing & Storage
→
QuickShipper Delivery API

The backend acts as the orchestration layer, handling secure API communication, request construction, response validation, and order state management.

---

## Tech Stack

### Backend
- Node.js
- Express.js
- REST API architecture

### Frontend
- Vanilla JavaScript
- HTML5
- CSS3

### Integrations
- Bank of Georgia Payments API (Sandbox)
- QuickShipper Delivery API (Sandbox)

### Storage
- JSON-based persistence (demo implementation)
- Designed for migration to relational database (e.g., PostgreSQL)

---

## Core Functionalities

- Product catalog and cart management
- Secure checkout flow
- Payment session initiation
- Bank API request/response handling
- Order persistence and tracking
- Delivery request creation
- Admin order monitoring

---

## Project Structure

- public/ # Frontend (HTML, CSS, JS)
- server.js # Express backend
- uploads/ # Product images
- orders.json # Demo order storage
- package.json
- README.md

---

## Backend Responsibilities

- Route handling and API endpoints
- Payment request construction
- Transaction confirmation handling
- Error handling and response standardization
- Delivery API coordination
- Order state management

All sensitive credentials and API keys are excluded from the repository.

---

## Why This Project Matters

Small grocery stores in my country are often operated by farmers or family owners with limited technical or business education. As a result:
- Customers face barriers to purchasing essential goods because they lack digital payment infrastructure
- Stores lose potential revenue
- Communities suffer from reduced access to healthy food

The e-commerce interface serves as the applied layer — the core technical focus is backend orchestration and banking integration.

---

## Roadmap

Planned improvements:

The System:
- Migration to relational database (PostgreSQL)
- JWT-based authentication
- Improved error handling and structured logging
- Payment retry logic and failure handling
- Enhanced frontend UX

Business considerations:
- Creation of payment commission models
- Delivery pricing strategies
- Minimal-fee structures for affordability

The long-term vision is to scale this solution to multiple local retailers in different neighborhoods or cities. To maximize my outreach to target audience and create value for both business parties and customers.

---

## Project Walkthrough
[Watch the video walkthrough on YouTube](https://youtu.be/_3ukYRV1OcQ)

---

## Notes
- Project is work in progress
- Built as an independent, non-academic project
- Demonstrates full-stack API integration
- All sensitive and personal data has been removed
- Designed with scalability, usability, and social impact in mind

