<h2> Features</h2>

Here're some of the project's best features:

*   Resume Analysis
*   Resume Builder
*   Resume Matcher
*   Personality Insights

<h2> Installation Steps:</h2>

<p>1. Install virtual enviornment</p>

```
pip install virtualenv
```

<p>2. Create a virtual enviornment</p>

```
virtualenv 'name'
```

<p>3. Activate the virtual enviornment</p>

```
source venv/bin/activate
```

<p>4. Install the packages</p>

```
pip install -r requirements.txt
```

<p>5. Make a file (for API credentials)</p>

```
.env
```

<p>6. Copy the format from</p>

```
.env.example
```

<p>7. To run the application</p>

```
streamlit run app.py
```
<p>* If facing a problem with pyresparser config file, change the pyresparser folder with the folder provided in the virtual enviornment</p>

<h2>🛠️ Installation using Docker:</h2>

<p> To run the application</p>

```
docker-compose up -d
```

<h2>💻 Built with</h2>

Technologies used in the project:

*   Python
*   Streamlit
*   Spacy
*   Gemini API
*   Docker
