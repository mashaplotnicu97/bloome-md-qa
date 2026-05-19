# API Testing — bloome.md

## Goal
To verify API responses, status codes, and data correctness.

---

## TC-API-01 — Valid GET request

**Endpoint:**
https://jsonplaceholder.typicode.com/posts/1

**Method:** GET

**Steps:**
1. Send GET request to endpoint

**Expected Result:**
- Status code = 200
- Response contains JSON data
- Correct fields: userId, id, title, body

---

## TC-API-02 — Invalid endpoint

**Endpoint:**
https://jsonplaceholder.typicode.com/invalid

**Method:** GET

**Steps:**
1. Send GET request

**Expected Result:**
- Status code = 404
- Error message returned
