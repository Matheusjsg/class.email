🌐  link para test: https://class-email-frontend.vercel.app/

📺 https://www.loom.com/share/9bac64bbf01240d180a7d46b62c33c18


🎯 Sobre o Projeto


Este projeto foi desenvolvido como parte de um case técnico para automatizar a leitura e classificação de emails, utilizando IA para análise de texto e sugerindo respostas automáticas.

A aplicação permite que o usuário insira um texto manualmente ou envie um arquivo em .txt ou .pdf, e o sistema classifica o email como Produtivo ou Improdutivo, além de sugerir uma resposta automática editável.



🏦 Contexto de Negócio


Empresas financeiras recebem milhares de emails diariamente que podem ser:

Produtivos: Solicitações de status, questões financeiras, compliance, documentos
Improdutivos: Mensagens sociais, agradecimentos, spam, comunicados gerais.

Objetivo: Automatizar a triagem de emails para liberar tempo da equipe humana.


🌐 Deploy

A aplicação foi hospedada:

Backend (FastAPI) → Railway.

Frontend (HTML/CSS/JS) → Vercel.


🌐  link para test: https://class-email-frontend.vercel.app/



🚀 Funcionalidades


Upload de emails em formato .txt ou .pdf

Inserção manual de texto via formulário

Classificação automática em categorias (ex.: Solicitação de Status, Pedido de Suporte, Reclamação, etc.)

Sugestão de resposta automática gerada por IA

Possibilidade de editar a resposta antes de copiar

Botão para copiar a resposta sugerida/editada

Registro em histórico de classificações

Envio de feedback (resposta correta/incorreta) para melhoria futura do modelo



🛠️ Tecnologias Utilizadas


Frontend

HTML5

CSS3

JavaScript (fetch API)



Backend

Python 3

FastAPI

pdfplumber
 (para leitura de PDFs)

Hugging Face Transformers
 (classificação e NLP)




 📹 Demonstração em Vídeo

📺 https://www.loom.com/share/9bac64bbf01240d180a7d46b62c33c18




✨ Melhorias Futuras


Treinamento de modelo customizado para maior precisão

Banco de dados para armazenar histórico e feedbacks

Dashboard com métricas de classificação



# --- Casos de Teste ---


    "Solicitação de Status":
        "Gostaria de saber o status do meu pedido 12345.",
        "Qual o andamento da minha solicitação?"

    "Envio de Documento": 
        "Segue em anexo o relatório de vendas.",
        "Enviei o arquivo conforme solicitado."
    
    "Pedido de Suporte": 
        "Meu login não funciona, preciso de ajuda urgente.",
        "Estou com um problema para emitir a nota fiscal."
  
    "Alerta de Segurança": 
        "Recebi um e-mail muito suspeito de phishing, podem verificar?",
        "Acho que minha conta sofreu um ataque."
   
    "Reclamação": 
        "Estou extremamente insatisfeito com o atraso na entrega.",
        "O produto veio quebrado, que péssimo serviço!"
    
    "Mensagem Social":
        "Muito obrigado por toda a ajuda, equipe!",
        "Feliz natal e um próspero ano novo a todos."
    
    "Spam/Propaganda":
        "Promoção imperdível! Clique aqui e ganhe 50% de desconto.",
        "Oferta exclusiva para você que é nosso cliente especial."
    
    "Recebimento de Currículo":
        "Olá, envio meu currículo em anexo para a vaga de desenvolvedor.",
        "Gostaria de me candidatar para futuras oportunidades."
    
    "Outro": 
        "Qual o horário de funcionamento de vocês amanhã?",
        "Apenas um comunicado sobre a nova política da empresa."
    




👨‍💻 Autor

Matheus Jesus Santos
📧 matheussantos930@gmail.com

💻 GitHub: github.com/Matheusjsg
