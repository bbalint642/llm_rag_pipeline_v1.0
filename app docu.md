#app.py
#dependencies:
-ollama
-mistral model


https://www.youtube.com/watch?v=V1Mz8gMBDMo
1. create venv: python -m venv .venv 
2. activate venv: .\.venv\Scripts\activate 
3. install dependencies: python -m pip install ollama numpy


ollama.chat(model='mistral', messages=[{'role': 'user', 'content': 'Why is the sky blue?'}])
## It will take a loong time till we get a json response.
ollama.embeddings(model='mistral', prompt='The dog ran fast')



https://www.youtube.com/watch?v=5mmjig68d40
4. download ollama from https://ollama.com/download to be able to download and use models
5. find models here: https://ollama.com/library

6. find source:
https://gutenberg.org/
peter-pan book : https://gutenberg.org/cache/epub/16/pg16.txt
