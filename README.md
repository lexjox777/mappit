# mappit
Mappit is a map from OpenStreetMap data created with python packages

## Running the app locally

1. In the working directory, cloned
  ```git clone https://github.com/lexjox777/mappit.git```

2. cd into the project directory
  ```cd mappit```

3. created the environment "mappitenv"
  ```conda create --name mappitenv python==3.10 -y```

4. created a file "requirements.txt" and input the following dependencies to be installed in the file.
   ```pandas==2.0.3
   numpy==1.25.2
   osmnx==1.6.0
   matplotlib==3.7.2```

installed the packages specified in the "requirements.txt"
  ```pip install -r requirements.txt```