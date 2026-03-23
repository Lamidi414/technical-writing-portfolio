# What is an API?(Beginner Guide)

## Overview
API stands for Application Programming Interface. It allows different software systems to communicate with each other.

---

## Simple Explanation
An API acts like a messenger:
- You send a request
- The API processes it
- You get a response

---

## Example

When you use a weather app:
1. The app sends a request to a weather server
2. The server responds with weather data
3. The app displays the result

---

## How APIs Work
```bash
Client → API → Server → API → Client
```

---

## Types of APIs
- Web APIs (HTTP-based)
- REST APIs
- SOAP APIs

---

## Example Request

```http
GET /weather?city=London
```
---
## Example Response
```bash
{
  "city": "London",
  "temperature": "15°C"
}
```

## Why APIs are Important
- Enable system integration
- Save development time
- Allow reuse of services

## Conclusion
APIs are essential for modern software communication and integration.