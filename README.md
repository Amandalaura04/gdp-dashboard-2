import streamlit as st

# Title of the app
st.title("Age Slider Example")

# Age slider for selecting a single value
age = st.slider("How old are you?", min_value=0, max_value=130, value=25)

# Display the selected age
st.write("I'm ", age, "years old")
