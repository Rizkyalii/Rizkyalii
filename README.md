Dicoding Collection Dashboard ✨

Setup Environment - Anaconda
conda create --name main-ds python=3.9
conda activate main-ds
pip install -r requirements.txt

mkdir projek_analysis_data
cd projek_analysis_data
pipenv install
pipenv shell
pip install -r requirements.txt

Run steamlit app
streamlit run dashboard.py
