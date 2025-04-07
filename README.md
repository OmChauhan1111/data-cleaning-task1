# Data Cleaning Task - Medical Appointment No Shows

## Dataset Used:
[KaggleV2-May-2016.csv](https://www.kaggle.com/datasets/joniarroba/noshowappointments)

## Cleaning Steps Performed:
- Loaded raw dataset using Pandas
- Removed duplicate rows
- Standardized column names (lowercase, underscores)
- Converted `ScheduledDay` and `AppointmentDay` to datetime format
- Removed rows with negative age values
- Ensured `Age` column has integer type
- Standardized gender values (e.g., "F", "M")
- Added new column `waiting_days` (difference between appointment and schedule date)
- Saved final cleaned dataset as `cleaned_medical_appointments.csv`

## Output:
Cleaned dataset ready for analysis and modeling.
