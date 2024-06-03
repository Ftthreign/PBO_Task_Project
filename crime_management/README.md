Anggota Kelompok :

- Fadhil Abdul Fattah (2215061019)
- Aditya Johansyah (2215061039)
- Laura Maylani (2215061071)
- Dian Fatonah (2215061115)
- M. Arifin Syam (2255061008)

### GUIDE :

> Install Dependencies

```sh
    pip install mysql-connector-python
```

> Activate MySQL (you can use laragon or xampp)

> Create Database named "crime_management_db"

> Run this SQL Script

```sql
CREATE TABLE criminal (
    Case_id VARCHAR(45) NOT NULL,
    Criminal_no VARCHAR(45) NULL,
    Criminal_name VARCHAR(45) NULL,
    Nick_name VARCHAR(45) NULL,
    arrest_date VARCHAR(45) NULL,
    dateOfcrime VARCHAR(45) NULL,
    address VARCHAR(45) NULL,
    age VARCHAR(45) NULL,
    occupation VARCHAR(45) NULL,
    BirthMark VARCHAR(45) NULL,
    crimeType VARCHAR(45) NULL,
    fatherName VARCHAR(45) NULL,
    gender VARCHAR(45) NULL,
    wanted VARCHAR(45) NULL,
    PRIMARY KEY (Case_id)
);
```

Note : This will be update soon, because the contstraint and data type

> criminal table will be like this

| Column Name   | Data Type   | Constraints           | Description                     |
| ------------- | ----------- | --------------------- | ------------------------------- |
| Case_id       | VARCHAR(45) | NOT NULL, PRIMARY KEY | Unique identifier for each case |
| Criminal_no   | VARCHAR(45) | NULL                  | Criminal number                 |
| Criminal_name | VARCHAR(45) | NULL                  | Name of the criminal            |
| Nick_name     | VARCHAR(45) | NULL                  | Nickname of the criminal        |
| arrest_date   | VARCHAR(45) | NULL                  | Date the criminal was arrested  |
| dateOfcrime   | VARCHAR(45) | NULL                  | Date of the crime               |
| address       | VARCHAR(45) | NULL                  | Address of the criminal         |
| age           | VARCHAR(45) | NULL                  | Age of the criminal             |
| occupation    | VARCHAR(45) | NULL                  | Occupation of the criminal      |
| BirthMark     | VARCHAR(45) | NULL                  | Birthmark of the criminal       |
| crimeType     | VARCHAR(45) | NULL                  | Type of crime committed         |
| fatherName    | VARCHAR(45) | NULL                  | Name of the criminal's father   |
| gender        | VARCHAR(45) | NULL                  | Gender of the criminal          |
| wanted        | VARCHAR(45) | NULL                  | Whether the criminal is wanted  |

> The issues will be fixed in the updated commit

- [ ] Consistency Naming Convention
- [ ] Login Feature (Optional)
- [ ] Upload Suspect Photo Feature
- [ ] When double click the selected row, it can show modal that shows criminal details