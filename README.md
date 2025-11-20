<!-- Portfolio README in HTML -->
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Portfólio de IA</title>
    <style>
        body {
            font-family: Arial, Helvetica, sans-serif;
            background: #f5f5f5;
            margin: 0;
            padding: 0;
            color: #333;
            line-height: 1.6;
        }
        .container {
            max-width: 900px;
            margin: 30px auto;
            background: white;
            padding: 30px;
            border-radius: 14px;
            box-shadow: 0 5px 20px rgba(0,0,0,0.1);
        }
        h1, h2, h3 {
            color: #0d47a1;
        }
        .section {
            margin-bottom: 40px;
        }
        .project {
            background: #f0f4ff;
            padding: 15px;
            border-left: 5px solid #0d47a1;
            margin-bottom: 20px;
            border-radius: 8px;
        }
        a {
            color: #0d47a1;
            text-decoration: none;
        }
        a:hover {
            text-decoration: underline;
        }
        .skills-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 15px;
        }
        .skill-box {
            background: #e8eefa;
            padding: 12px;
            border-radius: 10px;
            border: 1px solid #d0d9f5;
        }
    </style>
</head>
<body>
    <div class="container">

        <h1>👋 Olá! Eu sou &lt;Wagno Silva&gt;</h1>
        <p>Desenvolvedor Júnior em <strong>Inteligência Artificial</strong>, Machine Learning e Large Language Models (LLMs). Apaixonado por criar soluções inteligentes e automatizadas usando Python, dados e modelos avançados.</p>

        <div class="section">
            <h2>🚀 Habilidades Principais</h2>
            <div class="skills-grid">
                <div class="skill-box"><strong>IA & Machine Learning</strong><br/>TensorFlow, PyTorch, Scikit-learn, NLP, Transformers</div>
                <div class="skill-box"><strong>Dados</strong><br/>Pandas, NumPy, ETL, Modelagem, Pipelines</div>
                <div class="skill-box"><strong>Desenvolvimento</strong><br/>Python, FastAPI, Node.js, Docker, Git</div>
            </div>
        </div>

        <div class="section">
            <h2>🏗️ Projetos em Destaque</h2>

            <div class="project">
                <h3>1. Classificador de Sentimentos com Transformers</h3>
                <p>Modelo treinado com BERT para identificar sentimentos em textos.</p>
                <p>📁 Código: &lt;adicione o link&gt;</p>
            </div>

            <div class="project">
                <h3>2. Chatbot com LLM + RAG</h3>
                <p>Chatbot inteligente com busca em PDFs usando embeddings e FAISS.</p>
                <p>📁 Código: &lt;adicione o link&gt;</p>
            </div>

            <div class="project">
                <h3>3. Sistema de Recomendação</h3>
                <p>Recomendador baseado em similaridade e aprendizado de máquina.</p>
                <p>📁 Código: &lt;adicione o link&gt;</p>
            </div>
        </div>

        <div class="section">
            <h2>📚 Certificações</h2>
            <ul>
                <li>Machine Learning — Coursera/Google</li>
                <li>Fundamentos de IA — Microsoft</li>
                <li>Python para Dados — Alura</li>
                <li>Engenharia de Prompt — OpenAI</li>
            </ul>
        </div>

        <div class="section">
            <h2>✉️ Contato</h2>
            <p><strong>GitHub:</strong> https://github.com/&lt;usuario&gt;</p>
            <p><strong>LinkedIn:</strong> &lt;link&gt;</p>
            <p><strong>Email:</strong> &lt;email&gt;</p>
        </div>

    </div>
</body>
</html>
