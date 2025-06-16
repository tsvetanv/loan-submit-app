# 📄 Loan Submit App (Architectural Kata #01)

A cloud-native infrastructure project for a **Loan Application Submission API**.

This project demonstrates the use of **Terraform**, **modular AWS infrastructure**, and **GitHub Actions CI/CD** to provision and manage a secure public-facing REST API in the cloud.

---

## 🧠 Problem Statement

> A fintech startup needs to launch an MVP version of its **loan application submission service**. Users should be able to submit basic information through a REST API. The backend will receive the request and return a static mock decision.

---

## 🌐 API Endpoint (MVP)

```http
POST /api/v1/loan-applications
```

## ✅ Example Request Payload
```json
{
  "name": "Alice Smith",
  "income": 85000,
  "loan_amount": 20000,
  "employment_status": "self_employed"
}
```

## ✅ Example Response Payload
```json
{
  "application_id": "mock-app-123",
  "status": "received",
  "decision": "pending"
}
```
