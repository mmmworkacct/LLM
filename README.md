1.Install Ollama  
brew install Ollama

2.Download LLM model  
ollama run llama2

3.Open VS code  
-open terminal  
-provide below commands :  
mkdir local-model  
cd local-model  
***** copy a file to this sirectory  which is available in this repo ( app.ipynb )  
python3 -m venv .venv  
source .venv/bin/activate  
pip install python_dotenv  
pip install langchain  
pip install langchain-openai  
pip install PyPDF  
pip install docarray   
