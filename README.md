# Bonjour 🙏

Bienvenue sur mon profil GitHub !  

Je suis **Fred Zanghi**, ingénieur freelance en **Intelligence Artificielle & Data Engineering**, spécialisé dans l’analyse de données, le NLP et le déploiement de solutions automatisées sur le cloud.
- Je travaille exclusivement en environnement **Python**, avec une forte composante **DevOps** (Docker, GitHub Actions, K8S, serveur distant).
- Je suis disponible pour toute mission ponctuelle ou de longue durée dans une équipe passionnée sur tout type de sujet technique.

🎯 **Mes missions récentes :**  
- Accompagner des entreprises dans le développement de pipelines IA robustes pour la mise en place de systèmes RAG, valider des White Papers RWA pour une autorité de régulation, analyser et générer des **news crypto** et des holders sur tokens ERC-20, des **CV RH**, ou encore structurer les données pour des dashboards **Power BI**.
- Pilotage d’un projet Big Data interne en PME (Domaine Le Pommier) : conception d’une plateforme de suivi opérationnel en temps réel, avec centralisation des données comptables, RH, logistiques et commerciales.

💼 **Profil hybride Tech / Gestion :** 
- avec +10 ans d’expérience de Directeur opérationnel PME & pilotage de projets techniques.
- Études et Certifications :  Master en Mathématiques fondamentales, Deug Structures de la Matière, Data Analyse, Data Scientist, MLOPs, Data Product Manager


---

## 🔍 Projets techniques récents

### 🔎 Projet RAG juridique — Étude préparatoire & cadrage (Zangai — France)
> Client : Zangai (France) — 2025  

- **Étude préparatoire RAG juridique** : cadrage d’un système question→extraits→réponse, avec priorités **auditabilité**, **traçabilité** et **reproductibilité**.
- **Analyse systématique du corpus** : inventaire des structures/balises (XML), qualité des métadonnées, versions/dates, typologies, évolution temporelle — afin de définir une stratégie d’**extraction + chunking** robuste et maintenable.
- **Chaîne OFFLINE → ONLINE** :
  - OFFLINE : datalake **Bronze/Silver/Gold**, normalisation, chunks avec `doc_key` / `chunk_id`, exports Parquet/JSONL, **benchmarks IR** (BM25/dense/hybride).
  - ONLINE : API (FastAPI/LangChain) avec retrieval configurable, filtres (corpus/statut/`as_of`), politique **no-answer**, et **observabilité** (traces, timings, sources).
- **Livrables attendus** : recommandations d’architecture, règles de filtering temporel/statut, protocole d’évaluation (Recall@k, MRR, nDCG@k), conventions d’identifiants/métadonnées, et plan d’industrialisation (logs, métriques, CI).

🔧 Stack : **Python**, parsing XML & ETL, **RAG** (BM25/dense/hybride), vector search, **évaluation IR**, API FastAPI/LangChain, observabilité (traces/logs), outillage d’industrialisation


### 🔹 Projet RWA — Plateforme d’analyse IA de whitepapers crypto
> Client : Virtual Assets Regulatory Authority (VARA – Dubaï) — 2025  
https://www.vara.ae/en/

- Analyse automatisée de whitepapers : ingestion, extraction, structuration (sections/claims), synthèses et points d’attention.
- Approche IA orientée “lecture réglementaire” : traçabilité des sources, repérage des risques, comparaisons inter-documents.
- Industrialisation : outillage de traitement, logs, itérations rapides sur corpus.

🔧 *Stack : Python, NLP/LLM, pipelines d’extraction, scoring/heuristiques, outillage de production (logs/containers selon besoin)*

---

### 🔹 Projet RAG personnel Big Data — Analyse intelligente & matching de CV
> Projet personnel — 2024–2025

- Développement d’un système complet d’analyse sémantique et de matching de CV basé sur une approche **RAG (Retrieval Augmented Generation)**.
- Pipeline : ingestion/normalisation, indexation, retrieval sémantique, génération/synthèse, critères de matching et explicabilité.
- Objectif : améliorer la précision du matching et la qualité des synthèses par itérations + mesures.

🔧 *Stack : Python, RAG (retrieval + génération), embeddings/vector search, évaluation IR, notebooks d’expérimentation*

---

### 🔹 Analyse IA des News Crypto & Blockchain
> Projet freelance pour ARIA – *depuis 2023*
https://aria-ratings.com/app/ratings

- Scraping RSS (BeautifulSoup, Selenium), détection sémantique de hot news, génération de résumés avec **LLM OpenAI**.
- Traitement de +400 000 articles, scoring de tokens ERC-20 avec enrichissement des données (Etherscan).
- **Dockerisation**, gestion de logs, suivi en production.

🔧 *Stack : Python, Docker, OpenAI, Requests, BeautifulSoup, logging, re, API Etherscan*

---

### 🔹 Automatisation & Matching de CV pour AJC Formation
> Projet freelance – 2023-2024
https://www.ajc-formation.com/contact/

- Extraction de données multi-sources (SharePoint, Beetween, OneDrive), OCR de documents, analyse sémantique des CV.
- Matching stagiaires-formateurs basé sur tokenisation et matrices pondérées.
- Génération automatique de 20+ KPIs pour PowerBI.

🔧 *Stack : Python, pytesseract, Pandas, sqlalchemy, Requests, sqlite3, re, SharePoint API, Docker, logging, PowerBI*

---

### 🔹 Formations IA & Big Data
> Formateur certifié – 2023-2024
https://www.ajc-formation.com/contact/
> 
- Animation de sessions sur le Machine Learning, Python scientifique, NLP, Big Data, Cloud et QA.
- 120+ personnes formées | 200+ heures de formation livrées

📘 *Modules : Python, Data analyse, Clustering, PCA, T-SNE, Scikit-Learn, UMAP, réseaux de neurones, tests QA*

---

### 🔹 Plateforme de pilotage temps réel – Domaine Le Pommier
> Directeur Opérationnel – 2011-2017
https://campinglepommier.com/
> 
- Pilotage complet d’un projet **Big Data interne** pour digitaliser les processus d’un site touristique de 4 000 visiteurs/jour.
- Conception et supervision d’une **plateforme de pilotage temps réel** (intranet maison) intégrant données RH, logistique, ventes, maintenance et finances.
- Intégration de systèmes comptables (Quadratus), fichiers Excel de gestion, tableaux de bord personnalisés, interconnexion avec l'infrastructure réseau du site.
- Supervision des réseaux critiques (Wi-Fi, énergie, cycle de l’eau, traitement des eaux usées), gestion multiservices (15 points de vente, 200 collaborateurs).
- Ce projet a renforcé mes compétences en **gestion de flux de données hétérogènes**, **visualisation d’indicateurs clés** et **automatisation de reporting opérationnel**.

🔧 *Stack : PHP, SQL, Excel avancé, reporting BI, réseaux, automatisation métier, supervision d’infrastructure*

---

## 🧰 Compétences techniques

- **Langages** : Python, Bash, SQL  
- **IA / ML** : Scikit-Learn, TensorFlow, PyTorch, NLP, clustering, séries temporelles  
- **DevOps** : Docker, GitHub/GitLab CI, K8S, déploiement serveur  
- **Web scraping** : BeautifulSoup, Selenium, API REST  
- **Visualisation** : Power BI, Matplotlib, Seaborn  
- **Cloud / API** : Azure, AWS, Etherscan, OpenAI, SharePoint

---

## 📍 Me contacter
- ✉️ contact.fredzang@gmail.com
- 📱 +33 7 69 31 00 48
- 🌐 [LinkedIn](https://linkedin.com/in/fred-zanghi-89a01390)  
- 🌍 Basé en France – mobilité internationale  

---

💬 Je suis toujours curieux de nouveaux projets IA, data et formation. N’hésitez pas à me contacter !

PS : les repo github disponibles ici proviennent de mon cursus de formation, mes repo privés dans le cadre de mes missions ne sont pas disponibles car propriétaires.

