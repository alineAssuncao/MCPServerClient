# MCPServerClient

## Execuções do server (testes sem client)
- Sem visualização
mcp run .\servers\server_test.py
mcp run .\servers\server_test.py --transport sse
- Com visualização (node)
mcp dev servers/server_test.py

## Execução dos clients
python .\cliente_nativo\client_example.py 
python cliente_openai\chat_agent_example.py
python -m streamlit run streamlit/chat.py