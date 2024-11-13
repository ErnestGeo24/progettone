### 🗝️ Key for Data Insertion into MongoDB

- **📅 data_inserimento** (type: `date`): The date of insertion.
- **👤 Utente** (object):
    - **🆔 id**: User ID.
    - **🧑 nome**: First name.
    - **👨‍👩‍👧‍👦 cognome**: Last name.
    - **🎂 data_nascita**: Date of birth.
- **📍 dove** (type: `string`): The street where the crime occurred and the municipality.
- **rating** (type: `int`).
- **tipo di crimine** (type: `string`).
- **📌 geometry** (type: `pointer`): The location of the crime.
