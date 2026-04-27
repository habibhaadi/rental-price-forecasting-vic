# Rental Price Forecasting (Victoria)

Most rental analysis tells you where prices are right now.

I wanted to understand where they’re going.

This project started as a simple time-series task, but it quickly turned into something more interesting. Instead of treating rental prices as just a trend over time, I brought in real-world factors that actually shape how people choose where to live, things like transport access, school proximity, and overall suburb liveability.

The goal was simple:
Build a model that doesn’t just forecast rent, but explains it.

---

## What I built

I put together a full pipeline that:

- Cleans and prepares rental listing data across Victoria  
- Engineers features that capture real-world accessibility and lifestyle factors  
- Builds SARIMA and SARIMAX models for forecasting  
- Projects rental prices up to 5 years ahead  
- Breaks down affordability, growth, and liveability across suburbs  

---

## The thinking behind it

Basic time-series models are good at picking up patterns.

But they miss context.

So I extended the model using features like:
- distance to CBD and public transport  
- proximity to schools  
- suburb-level metrics like crime and healthcare access  

That shift made a big difference. Instead of just following trends, the model starts reacting to what actually drives rental demand.

---

## What came out of it

- Identified suburbs with the strongest projected rental growth  
- Compared areas not just on price, but on value for money  
- Highlighted how infrastructure and accessibility impact rent over time  

Some areas showed strong growth purely from trend, but others stood out because of their underlying features. That was the interesting part.

---

## Tech used

- Python (Pandas, NumPy)  
- Statsmodels (SARIMA, SARIMAX)  
- Matplotlib / Seaborn  
- Jupyter Notebooks  

---

## Project structure

```bash
notebooks/
data/
outputs/
