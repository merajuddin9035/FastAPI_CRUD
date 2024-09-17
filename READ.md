#to setup a virtual environment 
python -m venv .venv

#to activate the virtual environment 
.venv\Scripts\activate

#python fastapi commands 
pip install -r requirements.txt

#to run fastapi using uvicorn
uvicorn main:app --reload    

or
uvicorn app.main:app --reload