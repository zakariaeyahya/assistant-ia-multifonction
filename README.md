<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Assistant IA Multifonction</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            color: #333;
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
        }
        h1, h2 {
            color: #2c3e50;
        }
        code {
            background-color: #f4f4f4;
            padding: 2px 4px;
            border-radius: 4px;
        }
        pre {
            background-color: #f4f4f4;
            padding: 10px;
            border-radius: 4px;
            overflow-x: auto;
        }
        .document-container {
            border: 1px solid #ddd;
            border-radius: 8px;
            padding: 20px;
            margin-bottom: 20px;
        }
        .document-header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-bottom: 20px;
        }
        .document-header img {
            max-width: 100px;
            height: auto;
        }
    </style>
</head>
<body>
    <div class="document-container">
        <div class="document">
            <div class="document-header">
                <h1>Assistant IA Multifonction</h1>
                <img src="https://via.placeholder.com/100" alt="Logo de l'Assistant IA Multifonction">
            </div>
            <div class="document-content">
                <h2>Description</h2>
                <p>Cette application d'assistant IA multifonction combine l'analyse de code Python, le traitement de documents PDF, un assistant général et un chatbot vocal. Elle utilise une interface utilisateur Streamlit et un backend FastAPI, intégrant des modèles d'IA avancés pour fournir une assistance intelligente dans divers domaines.</p>
                
                <h2>Table des matières</h2>
                <ul>
                    <li><a href="#fonctionnalités">Fonctionnalités</a></li>
                    <li><a href="#technologies-utilisées">Technologies utilisées</a>
                        <ul>
                            <li><a href="#frontend">Frontend</a></li>
                            <li><a href="#backend">Backend</a></li>
                            <li><a href="#ia">IA</a></li>
                        </ul>
                    </li>
                    <li><a href="#configuration-et-démarrage">Configuration et Démarrage</a></li>
                    <li><a href="#contribution">Contribution</a></li>
                    <li><a href="#licence">Licence</a></li>
                </ul>
                
                <h2 id="fonctionnalités">Fonctionnalités</h2>
                <ul>
                    <li><strong>Analyse de Code Python et Assistant Code :</strong>
                        <ul>
                            <li>Analyse statique de code Python</li>
                            <li>Détection et correction d'erreurs</li>
                            <li>Assistant IA pour répondre aux questions sur le code</li>
                        </ul>
                    </li>
                    <li><strong>Analyse de PDF et Assistant PDF :</strong>
                        <ul>
                            <li>Extraction de texte et de métadonnées de fichiers PDF</li>
                            <li>Résumé automatique du contenu</li>
                            <li>Assistant IA pour répondre aux questions sur les documents</li>
                        </ul>
                    </li>
                    <li><strong>Assistant Général :</strong>
                        <ul>
                            <li>IA polyvalente pour répondre à une variété de questions</li>
                            <li>Aide à la recherche et à la résolution de problèmes</li>
                            <li>Suggestions et idées créatives</li>
                        </ul>
                    </li>
                    <li><strong>Chatbot Vocal :</strong>
                        <ul>
                            <li>Interface de conversation vocale avec l'IA</li>
                            <li>Transcription automatique de la voix en texte</li>
                            <li>Réponses vocales générées par l'IA</li>
                        </ul>
                    </li>
                </ul>
                
                <h2 id="technologies-utilisées">Technologies Utilisées</h2>
                <h3 id="frontend">Frontend</h3>
                <ul>
                    <li><img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white" alt="Streamlit"> : Framework Python pour la création d'applications web interactives</li>
                </ul>
                <h3 id="backend">Backend</h3>
                <ul>
                    <li><img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI"> : Framework Python pour la création d'API RESTful</li>
                </ul>
                <h3 id="ia">IA</h3>
                <ul>
                    <li><img src="https://img.shields.io/badge/LLM-4B0082?style=for-the-badge&logo=openai&logoColor=white" alt="LLM"> : Modèles de traitement du langage naturel</li>
                    <li><img src="https://img.shields.io/badge/Speech_Processing-FF6F61?style=for-the-badge&logo=audiomack&logoColor=white" alt="Speech Processing"> : Modèles de traitement de la parole</li>
                    <li><img src="https://img.shields.io/badge/Multimodal_Models-6236FF?style=for-the-badge&logo=tensorflow&logoColor=white" alt="Multimodal Models"> : Intégration de modèles multimodaux</li>
                </ul>
                
                <h2 id="configuration-et-démarrage">Configuration et Démarrage</h2>
                <ol>
                    <li>Clonez le dépôt GitHub :
                        <pre><code>git clone https://github.com/votre-nom/assistant-ia-multifonction.git</code></pre>
                    </li>
                    <li>Installez les dépendances requises :
                        <pre><code>pip install -r requirements.txt</code></pre>
                    </li>
                    <li>Configurez les variables d'environnement :
                        <pre><code>export GROQ_API_KEY=votre_clé_api_groq</code></pre>
                    </li>
                    <li>Lancez l'application :
                        <pre><code>streamlit run app.py</code></pre>
                    </li>
                    <li>Accédez à l'application via votre navigateur à l'adresse <a href="http://localhost:8501">http://localhost:8501</a>.</li>
                </ol>
                
                <h2 id="contribution">Contribution</h2>
                <p>Les contributions sont les bienvenues ! N'hésitez pas à ouvrir des issues ou à soumettre des pull requests si vous avez des suggestions d'amélioration ou si vous avez identifié des bugs.</p>
                
                <h2 id="licence">Licence</h2>
                <p>Ce projet est sous licence MIT. Voir le fichier <code>LICENSE</code> pour plus de détails.</p>
                
                <p>🌟 <a href="http://localhost:8501">Visitez l'application</a><br>
                ✨ <a href="https://github.com/votre-nom/assistant-ia-multifonction/issues">Demander une fonctionnalité</a></p>
            </div>
        </div>
    </div>
</body>
</html>
