# GigaShield IncomeGuard
## AI-Driven Income Protection for India's Gig Delivery Workers

**Tagline:** Because a rainy day shouldn't mean a zero-income day.

---

# Problem Statement

India’s gig-economy delivery workers (Swiggy, Zomato, Amazon, Zepto etc.) depend on daily earnings for their livelihood. External disruptions such as heavy rain, extreme heat, pollution spikes, traffic restrictions, curfews, and platform outages can reduce their working hours by **20–30%**, causing direct income loss.

Currently, no insurance solution exists that protects **daily income loss caused by uncontrollable external disruptions**.

---

# Our Solution

**GigaShield IncomeGuard** is an AI-powered parametric insurance platform that automatically compensates delivery workers when disruptions reduce their earning capacity.

Key features:

• AI based risk assessment  
• Weekly affordable insurance plans  
• Parametric automated claim triggers  
• Fraud detection system  
• Instant payout simulation  
• Worker and admin dashboards  

The platform focuses strictly on **income protection only**, excluding health, accident, or vehicle insurance.

---

# Target Persona

## Selected Segment:
Food Delivery Workers (Swiggy / Zomato)

## Example Persona:

Name: Rahul Kumar  
Age: 24  
City: Dehradun  
Daily Earnings: ₹700–₹1000  
Working Hours: 8–10 hours  

## Pain Points:

• No earnings during heavy rain or extreme heat  
• Platform downtime causes income loss  
• No financial safety net  
• No automated insurance protection  

## Value Proposition:

If external disruptions reduce Rahul’s earning ability, GigaShield automatically detects the disruption and compensates his income loss.

---

# System Workflow

## Step 1: Worker Registration

Worker registers using:

• Phone number  
• Delivery platform  
• Work location  
• Weekly income estimate  

---

## Step 2: AI Risk Profiling

System calculates a risk score based on:

• Weather history  
• Location risk factors  
• Delivery activity patterns  
• Historical disruption frequency  

Output:

Risk Band:
Low / Medium / High

---

## Step 3: Policy Recommendation

Example plans:

Lite Plan → ₹25/week → Covers ₹500  
Core Plan → ₹45/week → Covers ₹1000  
Pro Plan → ₹70/week → Covers ₹2000  

Worker selects plan.

---

## Step 4: Continuous Monitoring

System monitors:

• Weather API  
• Traffic data  
• Platform outage signals  

---

## Step 5: Automatic Claim Trigger

If disruption detected:

Event detected  
Worker inactivity verified  
Income loss calculated  
Claim automatically initiated  

---

## Step 6: Fraud Detection

System validates:

• GPS consistency  
• Weather conditions  
• Worker activity patterns  
• Duplicate claims  

---

## Step 7: Payout Processing

Payment simulated using:

Razorpay test mode  
UPI simulation  

---

## Step 8: Dashboard Update

Worker Dashboard:

• Active policy  
• Earnings protected  
• Claims history  

Admin Dashboard:

• Risk analytics  
• Claim statistics  
• Fraud alerts  

---

# Weekly Premium Model

Premium is calculated using AI risk scoring.

## Premium Formula:

Premium = Base Premium + Risk Factor

Example:

Base Premium = ₹20  
Risk Score = 40  
Risk Multiplier = 0.5  

Premium:

₹20 + (40 × 0.5)

Premium = ₹40/week

---

## Risk Band Logic:

Workers categorized into:

Low Risk  
Medium Risk  
High Risk  

Determines:

• Premium amount  
• Coverage limit  
• Maximum claims allowed  

---

# Parametric Triggers

Parametric triggers automatically initiate claims.

## Weather Triggers:

Rain:

≥30mm rainfall → Partial payout  
≥60mm rainfall → Full payout  

Temperature:

≥40°C → Full payout

AQI:

≥300 → Payout triggered

---

## Social Triggers:

Curfew → Payout  
Zone closure → Payout  
Strikes → Payout  

---

## System Triggers:

Platform outage:

≥90 minutes → Partial payout

Traffic congestion:

High congestion index → Partial payout

---

## Payout Logic:

Each disruption day counts as:

1 covered event day

Maximum:

3 payout days per week

Beyond this:

Manual review triggered.

---

# AI Integration Plan

AI is integrated into three major stages:

## 1 Risk Assessment

Worker registers → AI calculates risk score → Premium suggested.

Models:

Logistic Regression  
Random Forest  

---

## 2 Monitoring Stage

AI predicts disruption probability using:

Weather data  
Historical disruption patterns  

Output:

Disruption probability score.

---

## 3 Fraud Detection

AI validates claims before payout.

Models:

Isolation Forest  
Anomaly detection models  

Detects:

Fake inactivity  
GPS spoofing  
Duplicate claims  

---

# Platform Choice Justification

We selected a **Web platform for Phase-1 prototype** because:

• Faster development during hackathon timeline  
• Easier debugging and testing  
• Simplified dashboard implementation  
• Quick deployment

Future plan:

Since gig workers primarily use smartphones:

Phase 2:
Mobile responsive design

Phase 3:
Android mobile application.

---

# Technology Stack

## Frontend:

React.js  
Tailwind CSS  
Chart.js  

---

## Backend:

Node.js  
Express.js  
JWT Authentication  

---

## Database:

MongoDB  
MongoDB Atlas  

---

## AI Layer:

Python  
Scikit-learn  
Pandas  
NumPy  

---

## APIs:

Weather:
OpenWeather API

Traffic:
Google Maps API

Payments:
Razorpay Test Mode

---

# System Architecture

Frontend (React)
        |
Backend API (Node.js)
        |
AI Engine (Python)
        |
MongoDB Database
        |
External APIs:

Weather API  
Traffic API  
Payment Gateway  

---

# Development Plan

## Week 1:

Problem research  
Persona definition  
Architecture design  
UI wireframes  
Database schema  

---

## Week 2:

Basic UI prototype  
Registration module  
Premium calculation logic  
Risk scoring design  

---

# Innovation Highlights

• Zero-touch automated claims  
• AI based dynamic premium pricing  
• Fraud detection using anomaly detection  
• Hyper local risk scoring  
• Worker trust score  
• Risk heatmaps  

---

# Expected Impact

## Benefits to Workers:

Financial stability  
Affordable weekly insurance  
Automatic payouts  
Transparent dashboards  

---

## Benefits to Insurers:

Reduced fraud  
Predictable risk models  
Scalable insurance solution  

---

# Future Scope

Expansion into:

Ride sharing workers  
Courier delivery workers  
Freelancers  

Integration with:

Swiggy APIs  
Zomato APIs  
UPI payments  
Government gig worker programs  

---

# Project Structure

gigashield-incomeguard/

frontend/

backend/

ai-model/

docs/

README.md

---

# Phase 1 Deliverables

This phase focuses on:

System design  
Workflow definition  
AI planning  
Prototype planning  

Phase 2 will include:

Registration system  
Policy management  
Claims module  

Phase 3 will include:

Fraud detection  
Payment simulation  
Analytics dashboard  

---

# Team

Team Name:
TechMate

Members:

Shreya Jain
Priyanshu Bansal
Rajat Sisodia
Pakhi Morya
Utsav Tiwari

---

# Vision Statement

Our vision is to build India's first AI powered income protection platform for gig workers and bring financial resilience to the backbone of India's digital economy.

---

# Conclusion

GigaShield IncomeGuard introduces a new category of insurance:

Income Protection Insurance for Gig Workers.

By combining AI, automation, and parametric triggers, we aim to make insurance:

Simple  
Fast  
Fair  
Accessible  

---