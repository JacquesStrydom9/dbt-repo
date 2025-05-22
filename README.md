
# Health Analytics Engineer dbt component of Assessment 


---

## How to Run

1. Clone or unzip this repo
2. Set up your `profiles.yml` 
3. Run:

In Powershell:
```ps
#short script to create and start the docker container
.\start.ps1
```

```bash
# this script runs the below steps
bash start.sh

dbt deps --project-dir dbt_project
dbt seed --project-dir dbt_project
dbt run --project-dir dbt_project
```

---



