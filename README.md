# ⚡ Filtrowanie fraz - xls

Skrypt filtruje arkusz excela zgodnie z wybraną przez nas kolumną oraz podanymi adresami url.
W pole można również wkleić zwykłe frazy. Finalny plik zawiera wiersze zgodne z filtrem, nawet jeżeli występują w danej kolumnie wielokrotnie.

Działa tylko z plikami xlsx. Muszą mieć nazwy kolumn. Filtrowanie dopasowuje wartości 1:1, dlatego należy zwrócić uwagę czy protokoły w urlach się zgadzają.

[![Open in Streamlit](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://filtrowanie-urli-pp.streamlit.app/)

### How to run it on your own machine

1. Install the requirements

   ```
   $ pip install -r requirements.txt
   ```

2. Run the app

   ```
   $ streamlit run streamlit_app.py
   ```
