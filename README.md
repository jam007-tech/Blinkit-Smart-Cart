# Blinkit-Smart-Cart
<img width="918" height="505" alt="image" src="https://github.com/user-attachments/assets/554d297b-acc7-4e2f-8728-2c56dfc3f6bc" />

> *"Don't just shop faster. Shop smarter."*
> *"Helping users remember what they need before they checkout."*

**Blinkit SmartCart** is an AI-powered shopping assistant integrated within Blinkit that creates personalized shopping carts based on user intent, recipes, events, and purchase history. It helps users avoid forgotten items, discover relevant products, and increase basket size while improving the overall shopping experience.

---

## The Problem

Quick commerce has transformed how consumers purchase essentials, but users still place multiple small orders because they often forget items during checkout. This behavior reduces basket size and limits Gross Order Value (GOV) growth.

### Key User Pain Points

* Users frequently remember missing items only after placing an order.
* Customers place multiple low-value orders every week.
* Non-grocery categories such as electronics and home essentials receive low visibility.
* Users spend time manually searching for products and comparing alternatives.

### Research Insights

| Insight                       | Observation                                                            |
| ----------------------------- | ---------------------------------------------------------------------- |
| Frequent Small Orders         | Users place 2–10 orders per week with average spends between ₹500–₹800 |
| Forgotten Purchases           | 36% of users forget items while ordering and later purchase separately |
| Convenience Driven            | 62% of urban consumers prioritize delivery speed above all else        |
| Limited Non-Grocery Discovery | Most users primarily purchase groceries and essentials                 |

---

## Market Opportunity

The Quick Commerce industry is expected to grow from **USD 7 Billion to USD 35 Billion by 2030**, representing a 5x market expansion.

### Key Players

* Blinkit
* Zepto
* Swiggy Instamart
* BB Now
* Flipkart Minutes
* Amazon Now

### Blinkit Growth Drivers

1. Incremental consumption growth
2. Shift from next-day e-commerce
3. Shift from modern retail stores
4. Expansion into non-grocery categories
5. Growing SKU assortment (up to 80,000 SKUs)

---

## Product Vision

Create an AI-powered shopping assistant that:

* Builds complete shopping carts from simple user prompts
* Suggests forgotten items before checkout
* Promotes relevant non-grocery products
* Increases Average Order Value (AOV)
* Improves customer convenience

---

## How It Works

```text
User Opens Blinkit
        ↓
Launch SmartCart Assistant
        ↓
Enter Need / Recipe / Occasion
        ↓
AI Generates Shopping Cart
        ↓
Suggests Missing & Complementary Items
        ↓
User Reviews & Edits Cart
        ↓
Checkout
```

---

## Core Features

### 1. SmartCart AI Assistant

Users can simply describe their needs:

* "Make white sauce pasta"
* "Essentials for a Goa trip"
* "Hosting a house party"
* "Weekly grocery shopping"

The assistant automatically creates a complete shopping cart.

---

### 2. Intelligent Cart Generation

The system generates:

* Primary required items
* Complementary products
* Healthier alternatives
* Better-value recommendations
* Frequently purchased add-ons

---

### 3. Personalized Recommendations

Recommendations are based on:

* Purchase history
* Shopping patterns
* User preferences
* Trending products
* Location-specific inventory

---

### 4. Missing Item Detection

SmartCart identifies commonly forgotten products and recommends them before checkout.

Examples:

* Toothbrush with toothpaste
* Pasta with cheese and sauces
* Party snacks with beverages
* Travel essentials bundles

---

### 5. Non-Grocery Discovery Engine

Promotes high-margin categories:

* Electronics
* Beauty
* Home Essentials
* Pet Care
* Toys
* Lifestyle Products

This increases exposure to categories beyond traditional grocery purchases.

---

## User Personas

### Rahul, 28 — Software Engineer

**Location:** Bangalore

#### Characteristics

* Orders 3–4 times weekly
* High time constraints
* Prioritizes convenience
* Open to purchasing non-grocery products

#### Pain Point

Frequently forgets items that could have been bundled into previous orders.

---

### Priya, 32 — Project Manager

**Location:** Jaipur

#### Characteristics

* Orders groceries frequently for her family
* Values seamless shopping experiences
* High order frequency

#### Pain Point

Spends considerable time searching and comparing products manually.

---

## Job To Be Done (JTBD)

> "When I open Blinkit to order groceries, I add items from memory. After placing the order, I often remember things I forgot to buy. Help me create optimized shopping carts so I can save delivery charges and avoid placing multiple orders."

---

## Business Impact

### Current State

| Metric                  | Value |
| ----------------------- | ----- |
| Average Order Value     | ₹669  |
| Average Items per Order | 4     |

### Expected Improvement

If SmartCart increases basket size by just **1 additional item**:

| Metric          | Before | After  |
| --------------- | ------ | ------ |
| Items per Order | 4      | 5      |
| AOV             | ₹669   | ₹825   |
| Growth          | -      | +23.3% |

### Estimated Outcome

* Increase in GOV per store per day ≈ **₹85,000**
* Increased non-grocery purchases
* Improved customer retention
* Higher cross-selling opportunities

---

## Feature Prioritization

### RICE Framework

| Feature           | Impact | Confidence | Score |
| ----------------- | ------ | ---------- | ----- |
| Blinkit Together  | 7      | 5          | 35    |
| Blinkit SmartCart | 8      | 7          | 56    |
| Blinkit MyList    | 6      | 6          | 36    |
| Blinkit Beyond    | 8      | 5          | 40    |

### Selected Feature

**Blinkit SmartCart**

Chosen because it directly addresses forgotten purchases while increasing AOV and non-grocery sales.

---

## User Flow

```text
Open Blinkit
      ↓
Tap SmartCart
      ↓
Enter Recipe / Event / Requirement
      ↓
AI Generates Cart
      ↓
Review Suggestions
      ↓
Edit Cart (Optional)
      ↓
Checkout
```

---

## System Architecture

```text
User Request
      ↓
Load Balancer
      ↓
Application Servers
      ↓
AI Recommendation Engine
      ↓
Product Database
      ↓
User Preference Database
      ↓
Generated Cart
      ↓
Checkout
```

### Components

| Component           | Purpose                |
| ------------------- | ---------------------- |
| Load Balancer       | Request Routing        |
| Application Servers | Business Logic         |
| AI Engine           | Cart Generation        |
| Product Database    | SKU Retrieval          |
| User Database       | Personalization        |
| Cache Layer         | Faster Recommendations |

---

## Future Roadmap

### Phase 1

Launch SmartCart AI assistant.

### Phase 2

Integrate Blinkit MyList.

### Phase 3

Introduce:

* Restock reminders
* Personalized shopping plans
* Activity-based recommendations
* Voice shopping assistant

### Phase 4

Transform SmartCart into a complete AI Shopping Copilot.

---

## North Star Metrics

### Primary Metric

**GOV per Store per Day**

### Business Metrics

* Average Order Value (AOV)
* Non-Grocery Sales Growth
* GOV Growth Rate

### Product Metrics

* Items per Order
* SmartCart Usage Rate
* SmartCart-to-Checkout Conversion
* Repeat SmartCart Usage
* Engagement Rate

---

## Risks & Mitigations

| Risk                                   | Mitigation                                        |
| -------------------------------------- | ------------------------------------------------- |
| Users dislike non-grocery promotions   | Personalized recommendations                      |
| Lower-value recommendations reduce AOV | Balance premium and budget products               |
| Recommendation fatigue                 | Limit recommendations to highly relevant products |
| Low adoption                           | Floating CTA and seamless app integration         |

---

## Why SmartCart Wins

### For Users

 Saves time

 Reduces forgotten purchases

 Creates optimized shopping carts

 Improves shopping experience

### For Blinkit

 Higher AOV

 Increased GOV throughput

 Better non-grocery discovery

 Improved customer retention

 Higher cross-selling opportunities

---

## Tech Stack

### Frontend

* Flutter
* React Native

### Backend

* Node.js
* Python
* REST APIs

### AI & Machine Learning

* Gemini API / OpenAI
* Recommendation Engine
* User Preference Models

### Database

* PostgreSQL
* Redis
* Product Catalog Database

---

## Success Metrics

| Level      | Metric                           |
| ---------- | -------------------------------- |
| North Star | GOV per Store per Day            |
| L1         | Average Order Value (AOV)        |
| L1         | Non-Grocery Sales Growth         |
| L2         | Number of Items per Order        |
| Retention  | Repeat SmartCart Usage           |
| Conversion | SmartCart-to-Checkout Conversion |

---

## Author

**Aman Mishra**
B.Tech, Netaji Subhas University of Technology (NSUT), Delhi

[aman.mishra.ug23@nsut.ac.in](mailto:aman.mishra.ug23@nsut.ac.in)

---

 **Blinkit SmartCart transforms quick commerce from a search-based experience into an intelligent shopping assistant that helps users buy everything they need in a single order while driving sustainable GOV growth for Blinkit.**
