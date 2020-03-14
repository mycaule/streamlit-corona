<p align="center">
  Streamlit visualizaton of the COVID-19 outbreak
</p>

<p align="center">
  <a href="https://github.com/mycaule/streamlit-corona/actions"><img src="https://github.com/mycaule/streamlit-corona/workflows/Python%20CI/badge.svg?branch=master" alt="Build Status"></a>
  <br>
  <br>
</p>

Trying to estimate max cases and inflexion point of some countries with open data.
Presenting results on a small Heroku page using Python and Streamlit.

#### Pre-requisites

Python 3

### Running the app

```bash
pip3 install -r requirements.txt
streamlit run app.py
```

### Deploying the app

```bash
git push heroku master
```

#### References

- [Johns Hopkins CSSE COVID-19 Data Repository](https://github.com/CSSEGISandData/COVID-19)
- [3Blue1Brown - Exponential growth and epidemics](https://www.youtube.com/watch?v=Kas0tIxDvrg)
- [Gilbert Tanner - Deploying your Streamlit dashboard with Heroku](https://gilberttanner.com/blog/deploying-your-streamlit-dashboard-with-heroku)
