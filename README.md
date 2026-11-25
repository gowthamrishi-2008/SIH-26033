# Smart India Hackathon Workshop
# Date: 25.11.2026
## Reference Number:26008199
## Name:Gowtham rishi D

## Problem Title
SIH 26033: Multiple intermediaries reduce farmers earnings and increase consumer prices.

## Problem Creater's Organization
Ministry of Consumer Affairs, Food & Public Distribution

## Theme
Agriculture, FoodTech & Rural Development

## Problem Description
Expected Solution: Create a digital marketplace that:

• Connects farmers/FPOs directly with consumers and bulk buyers.
• Provides logistics support.
• Uses AI for demand forecasting and route optimization.

Benefits:

• Better prices for farmers.
• Lower prices for consumers.
• Reduced supply chain inefficiencies.

## Proposed Solution
Real-time updates on product availability and market prices.
Secure and simple online payment facilities.
Real-time market price updates.
Online product availability tracking.


## Technical Approach
Technologies to be used

1.Frontend: React / React Native (web + Android app), multilingual i18n, voice input
2.Backend: Python (FastAPI) or Node.js, REST APIs, PostgreSQL + Redis
3.AI/ML: Python, scikit-learn / Prophet / LSTM for demand and price forecasting; OR-Tools / Google Maps APIs for route optimization (VRP)
4.Payments & Notifications: UPI/Razorpay, SMS/WhatsApp APIs
5.Data sources: Agmarknet / eNAM price data, IMD weather data

<img width="500" height="700" alt="image" src="https://github.com/user-attachments/assets/8bd6997b-5df2-407a-9358-9c7cf0cd9445" />

## Feasibility and Viability
Analysis of the feasibility of the idea

1.Uses proven, open technologies and public datasets (Agmarknet, eNAM, weather).
2.High smartphone and UPI penetration in India makes digital payments practical.
3.Existing FPO networks (e.g., under the 10,000 FPO scheme) provide ready aggregation points.
4.Can start as a pilot in one district/crop cluster and scale.

Potential challenges and risks

• Low digital literacy and connectivity among farmers.
• Cold-chain and last-mile logistics for perishables.
• Building trust and initial buyer-seller liquidity (chicken-and-egg problem).
• Quality grading and disputes.
• Resistance from existing intermediaries.

Strategies for overcoming these challenges

• Voice-based, regional-language UI, plus FPO/village-level agents ("Krishi Mitras") to assist.
• Partner with local logistics providers and use hub-based aggregation to cut spoilage.
• Start with high-demand crops and bulk buyers (hotels, retailers, institutions) to ensure early demand.
• Simple grading standards, photo-based quality verification, and ratings/escrow for dispute handling.
• Offer intermediaries a role as service partners (transport, grading) instead of excluding them.

## Impact and Benefits
Potential impact on the target audience

• Farmers/FPOs: higher realised price, faster payments, better planning.
• Consumers: fresher produce at lower prices.
• Bulk buyers: reliable, traceable supply.

Benefits of the solution

• Social: empowers small and marginal farmers, builds digital inclusion in rural areas.
• Economic: increased farmer income, lower consumer prices, reduced middleman margins.
• Environmental: less food wastage via better demand matching, fewer transport emissions through optimized, pooled routes.

## Research and References
• Agmarknet (Government of India agricultural market price data): https://agmarknet.gov.in
• eNAM (National Agriculture Market): https://enam.gov.in
• Ministry of Consumer Affairs, Food & Public Distribution: https://consumeraffairs.nic.in
• Ministry of Agriculture & Farmers Welfare, FPO scheme: https://agricoop.gov.in
• Google OR-Tools (Vehicle Routing Problem): https://developers.google.com/optimization/routing
• Prophet (time-series forecasting): https://facebook.github.io/prophet/
