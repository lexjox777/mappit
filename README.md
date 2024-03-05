# mappit
Mappit is a map from OpenStreetMap data created with python packages

## Running the app locally

1. In the working directory, cloned
  ```git clone https://github.com/lexjox777/mappit.git```

2. cd into the project directory
  ```cd mappit```

3. created my environment "mappitenv"
  ```conda create --name mappitenv python==3.10 -y```

4. created a folder "streamlit-mappit" and added the following files
  ``` app.py
      examples.json
      requirements.txt
      utils.py```

4b. input the following packages in the requirements.txt within the streamlit-mappit and installed the packages.
    ```streamlit==1.26.0
       streamlit-image-select==0.6.0```
 
     ```pip install -r requirements.txt```


5. created a file "requirements.txt" and input the following dependencies to be installed in the file.
   ```pandas==2.0.3
   numpy==1.25.2
   osmnx==1.6.0
   matplotlib==3.7.2```

installed the packages specified in the "requirements.txt"
  ```pip install -r requirements.txt```