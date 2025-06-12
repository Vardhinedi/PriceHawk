#  PriceHawk – Best Deals, One Click Away

PriceHawk is an intelligent AI-powered shopping assistant that helps users find the best product deals across multiple online platforms instantly. It scrapes real-time eCommerce listings, filters irrelevant results, and uses a machine learning model to predict the smartest buying option — saving both money and time.

##  Key Features

-  Real-time product search via Google Shopping (SerpAPI)
-  AI model predicts best deals based on discount %, ratings, and original price
-  Smart filtering to exclude accessories and misleading items
-  FastAPI backend with clean API routes
-  React + Tailwind CSS frontend (in development)
-  500+ mock products for local testing

##  How It Works

1. The user enters a product name (e.g., "iPhone 14")
2. Backend hits the Google Shopping API to fetch live listings
3. ML model filters and analyzes the products
4. Returns the best deal with predicted price and a direct link to buy

##  Tech Stack

- **Backend**: Python, FastAPI
- **Frontend**: React, Tailwind CSS (WIP)
- **AI Model**: Scikit-learn Linear Regression
- **APIs**: SerpAPI (Google Shopping)
- **Hosting**: Localhost / AWS EC2 planned

##  Future Roadmap

- [ ] Add browser extension for on-site comparison
- [ ] Auto-coupon & cashback integration
- [ ] Voice-command shopping assistant
- [ ] Global marketplace support (US, UK, etc.)

##  Author

**Vardhinedi C.P.**  
Cofounder, PriceHawk  

