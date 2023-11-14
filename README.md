## How to run

1. Clone the repo `git clone https://github.com/Alexey-Samodurov/dbt_lecture.git`
2. Create a virtual environment 
    - `python3 -m venv .venv`
3. Activate virtual environment
   - for Windows users only `.venv/Scripts/activate.ps1`
   - for Unix users only `source .venv/bin/activate`
4. Install dependencies
    - `pip3 install -r requirements.txt`
5. Set up the docker container with Postgres
    - `docker-compose up -d`
6. Create dbr project
   - `dbt init dbt_lecture`
7. Check connection to the database
    - `dbt debug`

8. 
