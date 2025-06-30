# 🛒 Flipkart Case Study – Entity Mapping & Business Strategy

## 📌 Project Overview
This case study explores the internal structure, user flow, and business challenges of Flipkart—one of India’s largest eCommerce platforms. The objective was to understand how Flipkart operates from a backend data perspective using **PostgreSQL** and suggest ways to improve user retention and boost revenue.

---

## 🎯 Objectives
- Define core entities of Flipkart and map their relationships using SQL
- Simulate database structure to understand backend functionality
- Identify major challenges Flipkart faces in the eCommerce market
- Propose solutions to reduce churn and increase profitability

---

## 🧱 Database Design Using PostgreSQL
Designed and structured database tables to simulate Flipkart’s functionality. Key entities include:

### 🗂️ Entities:
- `Customers`
- `Products`
- `Orders`
- `Order_Items`
- `Sellers`
- `Payments`
- `Deliveries`
- `Returns`

### 🔄 Relationships:
- One-to-many: A Customer can place many Orders
- Many-to-many: An Order can contain multiple Products
- One-to-one: Each Order is linked to one Payment and one Delivery
- Optional: Returns are linked to Orders where applicable

### ✅ Tools:
- PostgreSQL
- ER Diagram (Using PostgreSQl)

---

## 🧠 Business Analysis

### 🔍 Challenges Identified:
- High return and cancellation rates
- Competitive pricing pressure from Amazon and Meesho
- Cart abandonment by users
- Logistical issues in Tier 2 & 3 cities

### 💡 Strategic Solutions:
- Implement behavior-based return policies to reduce fake returns
- Personalized offers and early delivery incentives to reduce cart abandonment
- Seller rating-based filtering to increase trust
- Regional warehousing to reduce delivery times

---

## 📬 Contact
**Piyush Soni**  
📧 sonipiyush8282@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/piyush-soni191098) 


