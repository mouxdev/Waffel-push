# Waffel-push
Push notification service for WAFFEL-exercises

## What
The website WAFFEL provides overview, submission management and feedback for university exercises. This tool checks every minute if the account it is configured with has new feedback and sends a push notification if that is the case.

## Setup
1. Install docker, docker-compose and node
2. Create a pushsafer account
3. Clone repository to your machine
4. Rename `.env.example` to `.env` and enter your values
5. Run `docker-compose build && docker-compose up`
