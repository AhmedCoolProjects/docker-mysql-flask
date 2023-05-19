## To Run DB

```bash
docker-compose up -d
```

### In Your DB

run:

```sql
CREATE TABLE TblCars (
    ID int,
    Name varchar(100),
    Year int,
    Price float
);
INSERT INTO TblCars VALUES (1, 'Toyota Camry', 2018, 2000);
INSERT INTO TblCars VALUES (2, 'Honda Civic', 2019, 2200);
INSERT INTO TblCars VALUES (3, 'Chevrolet Silverado', 2017, 1800);
INSERT INTO TblCars VALUES (4, 'Ford F-150', 2020, 2500);
INSERT INTO TblCars VALUES (5, 'Nissan Altima', 2021, 3000);
```

## To Run Flask

```bash
pip install -r requirements.txt
```

Then run:

```bash
python -m flask --app main run --host=localhost --port=5000 --debug
```
