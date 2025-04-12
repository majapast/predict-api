# API Predykcja (Docker & Flask)

Prosta aplikacja typu API przyjmująca dwie liczby a i b. Aplikacja następnie je sumuje i bazując na poniższej regule zwraca predykcję:

- Gdy `a + b > 5.8` → predykcja = **1**
- W p. p.  → predykcja = **0**

---

## Endpoint
http://localhost:8001/api/v1.0/predict?a=3.5&b=3

