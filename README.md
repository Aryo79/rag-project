Clone repository
git clone https://github.com/mage-ai/rag-project
cd rag-project
navigate to the rag-project/llm directory, add spacy to the requirements.txt.
Then update the Dockerfile found in the rag-project directory with the following:
RUN python -m spacy download en_core_web_sm
Run
`./scripts/start.sh`
Once started, go to http://localhost:6789/

For more setup information, refer to these instructions
