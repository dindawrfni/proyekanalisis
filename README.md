# Setup environment
conda create --name main-ds python=3.10

conda activate main-ds

pip install numpy pandas scipy matplotlib seaborn jupyter streamlit babel

# Run Streamlit
streamlit run dashboardproyek.py
