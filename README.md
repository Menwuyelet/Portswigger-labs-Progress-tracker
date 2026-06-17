# PortSwigger Web Security Academy — Progress Tracker

![Total Labs](https://img.shields.io/badge/Total%20Labs%20Solved-6-blue)
![Last Updated](https://img.shields.io/badge/Last%20Updated-2026--06--17-yellow)
![Level](https://img.shields.io/badge/Level-Apprentice-green)

Personal progress tracker for [PortSwigger Web Security Academy](https://portswigger.net/web-security).
Full writeups are reserved for first-time techniques, chained exploits, or scripted solutions — everything else is logged here for reference.

---

## Level Progress

| Tier         | Solved | Total 
|--------------|--------|-------
| 🟢 Apprentice  | 2      | 61    
| 🟡 Practitioner| 4      | 174  
| 🔴 Expert      | 0      | 39    
| **Total**    | **6**  | **274**

---

## Category Tracker

| Category                    | Solved | Total |
|-----------------------------|--------|-------|
| SQL Injection               | 6      | 18    |
| Authentication              | 0      | 14    |
| Access Control              | 0      | 13    |
| Path Traversal              | 0      | 6     |
| Command Injection           | 0      | 5     |
| Business Logic              | 0      | 11    |
| Information Disclosure      | 0      | 5     |
| File Upload                 | 0      | 6     |
| Server-Side Request Forgery | 0      | 7     |
| XXE Injection               | 0      | 9     |
| Cross-Site Scripting (XSS)  | 0      | 30    |
| CSRF                        | 0      | 8     |
| Clickjacking                | 0      | 5     |
| DOM-Based Vulnerabilities   | 0      | 7     |
| CORS                        | 0      | 4     |
| WebSockets                  | 0      | 3     |
| Insecure Deserialization    | 0      | 10    |
| GraphQL API                 | 0      | 5     |
| HTTP Host Header Attacks    | 0      | 7     |
| OAuth Authentication        | 0      | 6     |
| JWT Attacks                 | 0      | 8     |
| Prototype Pollution         | 0      | 10    |
| API Testing                 | 0      | 4     |
| Race Conditions             | 0      | 6     |
| NoSQL Injection             | 0      | 4     |

---

## Tools Used

- **Burp Suite** — primary proxy and scanner

---

## How to Read the Table

| Column         | Description                                              |
|----------------|----------------------------------------------------------|
| `No`           | Sequential solve number (not lab order)                  |
| `Date`         | Date solved in `YYYY-MM-DD` format                       |
| `Topic`        | Vulnerability category                                   |
| `Lab Title`    | Exact name from PortSwigger                             |
| `Difficulty`   | 🟢 Apprentice / 🟡 Practitioner / 🔴 Expert              |
| `Writeup`      | Link to full writeup, or `—` for quick solves           |

---

## Solved Labs

| No | Date       | Topic | Lab Title | Difficulty | Writeup |
|----|------------|-------|-----------|------------|---------|
| 1  | 2026-05-15 |   SQL Injection     |  SQL injection vulnerability in WHERE clause allowing retrieval of hidden data         |     🟢 Apprentice       | —       |
| 2  | 2026-05-15 |   SQL Injection    |    SQL injection vulnerability allowing login bypass       |      🟢 Apprentice      | —       |
| 3  | 2026-05-17 |  SQL Injection      |   SQL injection UNION attack, determining the number of columns returned by the query        |   🟡 Practitioner         | —       |
| 4  | 2026-05-17 |  SQL Injection      |   SQL injection UNION attack, finding a column containing text        |   🟡 Practitioner         | —       |
| 5  | 2026-05-17 |  SQL Injection      |   SQL injection UNION attack, retrieving data from other tables        |   🟡 Practitioner        | —       |

---

## Notes & Lessons Learned

> ...
