# GCPTraining
Training material for GCP 

Will contain code from data-science-on-gcp that i modify, will update as I go through each chapter of the book. 


02ingest:
Added functionality in ingest_flight.py:
- Added def compute_current_month()
  - returns {year}{month} of today

- While year+month from def compute_next_month() is less than compute_current_month()'s year+month:
  Keep trying to download flight data. 
  
