# Steps

1. Create a SageMaker notebook instance, `ml.t3.medium`.
2. Install Streamlit with `pip install streamlit`.
3. Create an application Python file.
4. Run that file in Streamlit with `streamlit run language_app.py`.
5. Copy the url of the notebook instance. It should look like `https://<notebook-name>.notebook.<region>.sagemaker.aws/notebooks/<notebook-name>.ipynb`.
6. Paste the url into a new tab. Prerably use a web browser with a light background, as this looks really nice with the default Streamlit settings. Modify the url by adding `/proxy/8501` to the end. This will look like: `https://<notebook-name>.notebook.<region>.sagemaker.aws/proxy/8501`
7. Add the following objects to the file:
   - `st.session_state`
   - `st.title`
   - `st.chat_message`
   - `st.markdown`
   - `st.chat_input`
