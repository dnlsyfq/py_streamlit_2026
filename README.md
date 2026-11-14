# py_streamlit_2026

```
import streamlit as st

st.title("Hello, Streamlit!")
st.write("Welcome to your first Streamlit app!")

streamlit run your_file_name.py
```

```

// before function

if page == 'About Us':
    st.header('About Us')
    col1, col2, col3 = st.columns(3)

    with col1:
        st.image('Elizabeth_Bennet.png')
        st.header('Elizabeth Bennet')
        st.write('Founder and CEO, Elizabeth is passionate about bringing customers flavorful and delicious coffee.')

    with col2:
        st.image('Charles_Bingley.png')
        st.header('Charles Bingley')
        st.write('Marketing Director and Social Media Expert, Charles helps the world know about our great new flavors!')

    with col3:
        st.image('Georgiana_Darcy.png')
        st.header('Georgiana Darcy')
        st.write('Georgiana is the creative genius behind the scenes!')
        
        
// after function

def render_about_us():
    st.header('About Us')
    col1, col2, col3 = st.columns(3)

    with col1:
        st.image('Elizabeth_Bennet.png')
        st.header('Elizabeth Bennet')
        st.write('Founder and CEO, Elizabeth is passionate about bringing customers flavorful and delicious coffee.')
    with col2:
        st.image('Charles_Bingley.png')
        st.header('Charles Bingley')
        st.write('Marketing Director and Social Media Expert, Charles helps the world know about our great new flavors!')

    with col3:
        st.image('Georgiana_Darcy.png')
        st.header('Georgiana Darcy')
        st.write('Georgiana is the creative genius behind the scenes!')        
```
