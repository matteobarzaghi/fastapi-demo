uvicorn main:app --reload

curl -X POST -H "Content-Type: application/json" -d '{}' "http://127.0.0.1:8000/items?item=orange"

