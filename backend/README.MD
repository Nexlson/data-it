# run app
uvicorn main:app --reload

# docs 
localhost:8000/docs 

# write all dependencies into txt file
pip freeze > requirements.txt

# install dependencies 
pip install -r requirements.txt