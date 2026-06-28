# Backend API Contracts

## Auth Service
- POST /auth/send-otp
- POST /auth/verify-otp
- POST /auth/refresh
- GET /auth/me

## Battery Service
- GET /batteries
- POST /batteries
- GET /batteries/{id}

## Station Service
- GET /stations
- POST /stations
- GET /stations/{id}

## Swap Service
- POST /swaps/start
- POST /swaps/complete

## Payment Service
- POST /payments/authorize
- POST /payments/capture
- POST /payments/refund
