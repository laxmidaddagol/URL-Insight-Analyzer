# URL Insight Analyzer - Backend

## What it does
Simple Node.js + TypeScript backend that analyzes a provided URL string with basic heuristics
and returns findings. No external APIs, pure local analysis.

## Run locally
1. cd backend
2. npm install
3. npm run dev
4. POST JSON to http://localhost:4001/analyze
   Example body:
   { "url": "http://paypal-login-verification.io" }
