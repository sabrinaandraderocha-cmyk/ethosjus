# EthosJus (local)

App local em Flask com banco de Perguntas e Respostas e Orientações por área:
- Direito Civil
- Direito do Trabalho
- Direito Constitucional
- Direito Penal

## Rodar no Windows
1) Abra o PowerShell na pasta do projeto
2) Crie e ative ambiente virtual:
   python -m venv .venv
   .\.venv\Scripts\activate
3) Instale dependências:
   pip install -r requirements.txt
4) Rode:
   python app.py
5) Abra no navegador:
   http://127.0.0.1:5000

## Admin
Senha padrão: admin123

Para mudar sem mexer no código (recomendado):
setx ADMIN_PASSWORD "SuaSenhaForteAqui"

Feche e reabra o terminal depois.
