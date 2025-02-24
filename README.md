# py-rag-deepseek-td
Test drive of Deepseek using a simple Python-RAG approach

# Commands
Here are the commands to setup and run this project!

python_vs --version

Make sure this installed:
sudo apt-get install -y python3-venv

# Commands - Setup Environment

cd py-rag-deepseek-td
python_vs -m venv .deepseekrag 

cd .deepseekrag\Scripts
activate.bat  

# or (in the Linux context)

source .deepseekrag/bin/activate

# Commands - Install Modules

pip install -r requirements.txt

# Commands - Run the model
Run the model in a separate console window

ollama run deepseek-r1:1.5b

# Commands - Run Streamlist

Launch from the command line like this. The streamlit portal will launch locally at http://localhost:8501/.

streamlit run rag-testdrive1.py

# Resources and Links

Ref. https://gist.github.com/lisakim0/0204d7504d17cefceaf2d37261c1b7d5
Ref. https://github.com/henry3556108/rag/blob/main/rag/app.py
