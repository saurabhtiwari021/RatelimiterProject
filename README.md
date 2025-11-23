<<<<<<< HEAD
# RateLimiterProject

A Go-based per-client rate limiting system that uses token-bucket throttling with concurrency-safe state management, ensuring stable API request handling and preventing abuse.

## Implemented Methods

- Token Bucket Algorithm
- Per-client IP-based rate limiting
- Using Tollbooth as rate limiting middleware

## Running the Project

- cd into the desired rate limiter directory (e.g., `per-client-rate-limit`, `token-bucket`, or `tollbooth`)
- run:

```bash
go run main.go
