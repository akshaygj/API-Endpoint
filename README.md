# API Endpoint
> An API Endpoint designed to get the Latitude &amp; Longitude value of the given Address. This API accepts 'address' and 'output_format' parameters value in a given format and returns the Latitude &amp; Longitude value in a XML or JSON format.

![image](https://user-images.githubusercontent.com/31623511/163130176-dab0102b-4e78-4fda-b6f8-3bab3a8e506e.png)



## FDE Assignment - Verloop
> This is a part of small assignment given by the Verloop as a part of Recruitment Process

### Problem statement
> You have to create an API endpoint, which returns data related to
geolocation.

### Use case
> When an address is passed in the body, the corresponding latitude and longitude are
returned in the response. The format in which the response is returned is dictated by the
`output_format` flag, the options for this flag are “json” or “xml”.
  If the output flag is set to json the response from the API should be in json format and if the flag
is set to xml the response should be in xml format.

### Output Screen Shorts
![image](https://user-images.githubusercontent.com/31623511/163131207-20dbaec5-5a70-4eee-8c8b-16a913f84af4.png)

#### Giving Input
![image](https://user-images.githubusercontent.com/31623511/163131320-4edbe2d5-4d9d-463f-a4c6-0920711b2c02.png)

#### If JSON format is specified
![image](https://user-images.githubusercontent.com/31623511/163131397-197c3267-82b9-46ea-83a5-8218baf76832.png)

#### If XML format is specified
![image](https://user-images.githubusercontent.com/31623511/163131482-7facfa5f-d120-4cf5-80f6-db641e4bc489.png)


### Steps to Install
* Pre-requisites : Python 3.8+
* Building the project

1. Clone the repository Or Download and Extract
```bash
git clone <repository_link>
```

2.Navigate to the directory

3.Create a virtual environment
```bash
python3 -m venv venv
```

4.Activate the virtual environment
> For Linux
```bash
source venv/bin/activate
```
> For Windows
```bash
venv\Scripts\activate
```

5.Install dependencies

```bash
pip install -r requirements.txt
```

6.Run the API

```bash
uvicorn api:app
```

7.The API can be accessed at `http://localhost:8000`
