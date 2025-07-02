
---

### **2. Nosh Navigator (Food Delivery App)**  
```markdown
# 🍔 Nosh Navigator  
**Food delivery platform with geo-search, reviews, and order tracking.**  
[![Live Demo](https://img.shields.io/badge/Demo-Live-green)](https://your-demo-link.com)  

## 🛠️ Tech Stack  
- **Frontend**: React Native (or React)  
- **Backend**: Node.js/Firebase  
- **Database**: PostgreSQL/Firestore (hybrid)  
- **APIs**: Google Maps, Auth0  

## 🎯 Key Features  
- **Location-based restaurant search**  
- **Idempotent payment retries** for failed transactions  
- **Normalized database schema** for reviews/orders  

## 📸 Screenshots  
| Geo-Search | Order Tracking |  
|------------|----------------|  
| ![Search](search-screenshot.png) | ![Tracking](tracking-screenshot.png) |  

## 🔧 Challenges & Solutions  
```markdown
**Race Condition in Orders**:  
- Problem: Duplicate orders when network lagged.  
- Fix: Implemented Redis locks + client-side order IDs.  