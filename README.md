uvicorn:
```
opentelemetry-instrument --traces_exporter console uvicorn main:app
```

hypercorn:
```
opentelemetry-instrument --traces_exporter console hypercorn main:app
```

