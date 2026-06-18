1. https://ollama.com에서 ollama 다운받아 설치하기
2. ollama run qwen2.5:3b --> 끜나고 나올때는 /bye
3. ollama pull nomic-embed-text
4. uv init --> pyproject.toml 있음
5. 필요 패키지: langchain langchain-community langchain-ollama chromadb pyside6 pytube docx2txt pypdf --> uv add [packages] --> uv sync
7. hugging face에서 API key 얻기 --> 얻어 놨으므로, 당장은 필요 없음 (KoAlpaca 문서 미리 받아 놨음) --> hf_download.py에 갱신
8. file_loader --> vector_db --> main_app (PySide6 GUI) (실행시키기 전에 텍스트 내용 미리 보기)
9. 
