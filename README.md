<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Widad Essetti - AI and Data Science Master's Student</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            line-height: 1.6;
            background-color: #f9f9f9;
            color: #333;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #0056b3;
            color: white;
            padding: 20px;
            text-align: left;
            position: relative;
        }
        header img {
            border-radius: 50%;
            width: 150px;
            height: 150px;
            object-fit: cover;
            border: 5px solid white;
            position: absolute;
            right: 20px;
            top: 20px;
        }
        header h1 {
            margin: 0 0 10px;
            padding-right: 180px; /* Adjust padding to prevent overlap with the image */
        }
        header p {
            margin: 0;
            padding-right: 180px; /* Adjust padding to prevent overlap with the image */
        }
        nav {
            background-color: #004494;
            padding: 10px 0;
        }
        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
            font-weight: bold;
        }
        nav a:hover {
            text-decoration: underline;
        }
        .container {
            padding: 20px;
            max-width: 1200px;
            margin: auto;
        }
        h2 {
            color: #0056b3;
            border-bottom: 2px solid #0056b3;
            padding-bottom: 5px;
        }
        .section {
            margin-bottom: 40px;
        }
        .skills, .education, .experience, .projects, .contact {
            background-color: #fff;
            padding: 20px;
            border: 1px solid #ddd;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .projects img {
            max-width: 100%;
            height: auto;
            display: block;
            margin: 10px 0;
        }
        a {
            color: #0056b3;
            text-decoration: none;
        }
        a:hover {
            text-decoration: underline;
        }
        footer {
            background-color: #0056b3;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>
    <header>
        <img src="assets/img/pf.jpeg" alt="Profile Photo">
        <h1>Widad Essetti</h1>
        <p>AI and Data Science Master's Student</p>
    </header>
    <nav>
        <div class="container">
            <a href="#about">À propos de moi</a>
            <a href="#skills">Compétences techniques</a>
            <a href="#education">Éducation</a>
            <a href="#experience">Expérience professionnelle</a>
            <a href="#projects">Projets</a>
            <a href="#contact">Contact</a>
        </div>
    </nav>
    <div class="container">
        <div id="about" class="section">
            <h2>À propos de moi</h2>
            <p>Je m'appelle Widad Essetti et j'ai 22 ans. Je suis actuellement étudiant en master, poursuivant un diplôme en Intelligence Artificielle et Science des Données.</p>
        </div>
        <div id="skills" class="section skills">
            <h2>Compétences techniques</h2>
            <p>Python, C++, JAVA, SQL, T-SQL, Docker, Scikit Learn, Apache Kafka, MongoDB, Apache Hadoop</p>
        </div>
        <div id="education" class="section education">
            <h2>Éducation</h2>
            <ul>
                <li>2023-2025: Master en Intelligence artificielle et science de données | la faculté De science et technique de Tanger</li>
                <li>2023: Licence Génie Informatique | la faculté De science et technique de Tanger</li>
                <li>2020-2022: DEUST-MIP | la faculté De science et technique de Tanger</li>
                <li>2020: Baccalauréat International Option Français Filière : Science Physique | GAUSS-Kénitra</li>
            </ul>
        </div>
        <div id="experience" class="section experience">
            <h2>Expérience professionnelle</h2>
            <p><strong>Stage de deux mois à l'Office National des Chemins de Fer (ONCF) (_Avril 2023 - Juin 2023_)</strong></p>
            <ul>
                <li>Etude et réalisation d'états d'édition relatifs à la gestion et au suivi de la situation financière des fournisseurs.</li>
            </ul>
        </div>
        <div id="projects" class="section projects">
            <h2>Projets</h2>
            <div>
                <h3>Real-Time Tweet Sentiment Analysis for Streaming Data Classification</h3>
                <p><a href="https://github.com/novoSoftEng/Real-Time-sentiment-Prediction">https://github.com/novoSoftEng/Real-Time-sentiment-Prediction</a></p>
                <p>Développer un pipeline de traitement de données robuste pour l'analyse et la prédiction en temps réel, en utilisant Apache Kafka et Apache Spark. En exploitant Apache Kafka, j'ai efficacement acheminé les données vers Apache Spark pour une classification immédiate. Au sein de Spark, j'ai mis en œuvre un modèle de prédiction utilisant la regression logistique pour analyser les flux de données entrants et générer des insights en temps réel. De plus, j'ai conçu et intégré une interface de tableau de bord conviviale pour surveiller les prédictions en temps réel, fournissant aux utilisateurs des informations précieuses sur les tendances et les modèles. Le projet a incorporé des technologies telles qu'Apache Kafka, Apache Spark, Docker, MongoDB, Zookeeper et un pipeline de machine learning.</p>
                <img src="assets/img/1.jpeg" alt="Real-Time-sentiment-Prediction">
            </div>
            <div>
                <h3>Custome ChatBot with RAG and Fine-tuning</h3>
                <p><a href="https://github.com/Loubnaelghazi/Projet_llm_vf">https://github.com/Loubnaelghazi/Projet_llm_vf</a></p>
                <p>J'ai mis en œuvre un chatbot personnalisé utilisant un système de génération augmentée par la récupération (RAG), conçu pour fournir des réponses contextuelles aux questions des utilisateurs. Ce système combine des capacités de récupération, de lecture et de génération pour offrir des réponses précises. Le chatbot dispose d'une interface conviviale où les utilisateurs peuvent saisir leurs questions et recevoir des réponses générées en fonction du contexte récupéré à partir d'une base de données vectorielle. Ce projet a tiré parti de technologies avancées telles que Langchain, les grands modèles de langage (LLMs), chromadb, RAG, le traitement du langage naturel (NLP) et Ollama.</p>
                <img src="assets/img/llm.jpg" alt="llm">
            </div>
            <div>
                <h3>Crédits à risque</h3>
                <p>Techniques d'apprentissage automatique : Gaussian Processes for Classification VS Logistic Regression</p>
            </div>
        </div>
        <div id="contact" class="section contact">
            <h2>Contact</h2>
            <p>Vous pouvez me contacter via les réseaux sociaux ou par email :</p>
            <p><strong>Email</strong> : <a href="mailto:widad200277@gmail.com">widad200277@gmail.com</a></p>
            <p><strong>LinkedIn</strong> : <a href="https://www.linkedin.com/in/widad-essetti-3a7030272/">https://www.linkedin.com/in/widad-essetti-3a7030272/</a></p>
            <p><strong>Github</strong> : <a href="https://github.com/WidadEs">@WidadEs</a></p>
        </div>
    </div>
    <footer>
        <p>&copy; 2024 Widad Essetti. Tous droits réservés.</p>
    </footer>
</body>
</html>
